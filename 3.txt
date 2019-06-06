numbers=[]
n=input("enter the n.o of elements in the list")
print("enter the elements of the list")
for x in range (0,n):
	m=input()
	numbers.append(m)
y=input("enter the n.o to be searched");
float=1
big=0
end=n
while big<end:
	mid=(big+end)/2
	if number[mid]==y:
		print("n.o found")
		float=0
	elif number[mid]<y:
		big=mid+1
	else:
		end=mid-1
if float==1:
	print("n.o not found")

	

