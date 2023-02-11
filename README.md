# CHARACTER-CHECKER-FOR-UPPERCASE-AND-LOWERCASE
// PROGRAM TO FIND IF A CHARACTER ENTERED BY USER IS UPPERCASE OR LOWERCASE
#include<stdio.h>
int main(){
    char ch;
    printf("ENTER YOUR CHARACTER = ");
    scanf("%c",&ch);
    if (ch>='a' && ch<='z'){
        printf("LOWERCASE CHARACTER"); // to check whether a character is lowercase or uppercase compiler gonna use charcater's ascii value
    }
    else if (ch>='A' && ch <= 'Z') {
        printf("UPPERCASE CHARACTER");

    }
    else {
        printf("INVALID ENGLISH CHARACTER");

    }
    return 0;
}
