# stack
#include<stdio.h>
#include<stdlib.h>
#define MAX 5
int a[MAX],top=-1;
void push(int x)
{
        if(top==MAX-1)
        {
                printf("stack overflowen");
        }
        else
        {
                a[++top]=x;
        }
}
int pop()
{
        int x;
        if(top==-1)
                return -1;
        else
        {
                x=a[top];
                top--;
                return x;
        }
}
int peek()
{
        return a[top];
}
int display()
{
        int i;
        if(top==-1)
        {
                printf("there are no elements to display");
        }
        else
        {
                for(i=top;i>=0;i--)
                {
       
                        printf("\n%d",a[i]);
                }
        }
}
void main()
{
        int x;
        while(1)
        {
        printf("\nenter your choice \n1.push \n2.pop \n3.peek \n4.display \n5.exit");
        scanf("%d",&x);
        switch(x)
        {
                case 1:
                        printf("enter element to insert");
                        scanf("%d",&x);
                        push(x);
                        break;
                case 2:
                        x=pop();
                        if(x==-1)
                        {
                                printf("stack underflown");
                        }
                        else
                        {
                                printf("the element deleted is=%d",x);
                        }
                        break;
                case 3:
                        x=peek();
                        printf("the element in the top of the stack is %d",x);
                        break;
                case 4:
                        printf("the elements in the stack are:");
                        display();
                        break;
                case 5:
                        exit(0);
}
}
}                                                                                                                           
#include<stdio.h>
#include<stdlib.h>
#define MAX 5
int a[MAX],top=-1;
void push(int x)
{
        if(top==MAX-1)
        {
                printf("stack overflowen");
        }
        else
        {
                a[++top]=x;
        }
}
int pop()
{
        int x;
        if(top==-1)
                return -1;
        else
        {
                x=a[top];
                top--;
                return x;
        }
}
int peek()
{
        return a[top];
}
int display()
{
        int i;
        if(top==-1)
        {
                printf("there are no elements to display");
        }
        else
        {
                for(i=top;i>=0;i--)
                {
       
                        printf("\n%d",a[i]);
                }
        }
}
void main()
{
        int x;
        while(1)
        {
        printf("\nenter your choice \n1.push \n2.pop \n3.peek \n4.display \n5.exit");
        scanf("%d",&x);
        switch(x)
        {
                case 1:
                        printf("enter element to insert");
                        scanf("%d",&x);
                        push(x);
                        break;
                case 2:
                        x=pop();
                        if(x==-1)
                        {
                                printf("stack underflown");
                        }
                        else
                        {
                                printf("the element deleted is=%d",x);
                        }
                        break;
                case 3:
                        x=peek();
                        printf("the element in the top of the stack is %d",x);
                        break;
                case 4:
                        printf("the elements in the stack are:");
                        display();
                        break;
                case 5:
                        exit(0);
}
}
}                                                                                                                           


enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit1
enter element to insert30

enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit1
enter element to insert24

enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit1
enter element to insert45

enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit2
the element deleted is=45
enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit3
the element in the top of the stack is 24
enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit3
the element in the top of the stack is 24
enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit4
the elements in the stack are:
24
30
enter your choice 
1.push 
2.pop 
3.peek 
4.display 
5.exit5

