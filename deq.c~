//sample

#include<stdio.h>
#include<conio.h>


void enQueue(int);
void deQueue();
void display();

int a[30], front = -1, rear = -1;

void main()
{
   int ch, in;
   clrscr();
   do
	{
     	 printf("\n\n***** MENU *****\n");
      	printf("1. Insertion\n2. Deletion\n3. Display\n4. Exit");
      	printf("\nEnter your choice: ");
     	 scanf("%d",&choice);
     	 switch(choice){
		 case 1: enQueue();
			 
		 case 2: deQueue();
			 break;
		 case 3: display();
			 break;
		 case 4: exit(0);
	 	default: printf("\nWrong selection!!! Try again!!!");
      }	
   }
}
void eque(int value){
   if(rear == SIZE-1)
      printf("\nQueue is Full!!! Insertion is not possible!!!");
   else{
      if(front == -1)
	 front = 0;
      rear++;
      queue[rear] = value;
      printf("\nInsertion success!!!");
   }
}
void dque(){
   if(front == rear)
      printf("\nQueue is Empty!!! Deletion is not possible!!!");
   else{
      printf("\nDeleted : %d", queue[front]);
      front++;
      if(front == rear)
	 front = rear = -1;
   }
}
void display(){
   if(rear == -1)
      printf("\nQueue is Empty!!!");
   else{
      int i;
      printf("\nQueue elements are:\n");
      for(i=front; i<=rear; i++)
	 printf("%d\t",queue[i]);
   }
}

Output
//ok

