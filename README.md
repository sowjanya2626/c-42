# c-42
Pointers using arrays
#include <stdio.h>
int main() {
    int arr[]={10,20,30};
    int *ptr=arr;
    for(int i=0;i<3;i++){
        printf("element %d\n",*(ptr+i));
    }
    return 0;
}
