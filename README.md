#approach-1
n=int(input())
d={}
s=0
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
for j in d:
  s=s+d[j]
print(s)

#Approach-2
n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
res=d.values()
print(sum(res))

