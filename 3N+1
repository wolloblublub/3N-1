from timeit import default_timer as timer
class calculator():
    def Main():
        n=int(input("Please enter a starting number: "))
        s=int(input("Please enter a ending number: "));s+=1
        start = timer()
        for i in range(n,s):
            c = 0
            p = n
            while n >1:
                if (n%2==0):
                    n = n/2;c +=1
                else:
                    n = 3*n+1;c +=1
            print (p,"=",c);n = p+1
        end = timer();print(end - start,"Seconds")  
    Main()
