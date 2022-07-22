# runner
if __name__ == '__main__':
    n = int(input())
    arr = list(map(int, input().split()))
    a=max(arr)
    c=0
    c=arr.count(a)
    for i in range(c):
        arr.remove(a)
    print(max(arr))
    
