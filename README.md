# python-basicsL = input().split()
L2 = [L[0]]

for i in range(1,len(L)-1) :
    L2.append(L[i][::-1])
L2.append(L[-1])
print(*L2,end='')
