def recurfact(n):
    if n==0:
        return 1
    else:
        return n*recurfact(n-1)

num=int(input("num: "))
if num<0:
    print("factorial not exist for negative number")
else:
    print("factorial:",recurfact(num))
