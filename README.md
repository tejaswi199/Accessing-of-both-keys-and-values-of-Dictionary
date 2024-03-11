#Approach-1
n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
for j in d:
  print(j,d[j],sep='->')

 #Approach-2 
n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
for j in d:
  print(f"{j}->{d[j]}")
  
