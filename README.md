# Convert-String-into-Uppercase
#include &lt;stdio.h> #include &lt;ctype.h> int main() {     char s[100];     int i;     fgets(s,sizeof(s),stdin);     for(i=0;s[i]!='\0';i++)         s[i]=toupper((unsigned char)s[i]);     printf("%s",s);     return 0; }
