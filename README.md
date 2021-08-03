# 2.md\
#include <stdio.h>
#include <conio.h>
int main()
{
	const char* name = "신영";
	int age;
	int height;
	printf("당신의 키를 cm단위로 입력하세요");
	scanf("%d", &height);
	printf("\n나이도 입력해주세요");
	scanf("%d", &age);
	printf("안녕하세요.\n%s씨\n", name);
	printf("반갑습니다.\n");
	printf("저는 %d살이에요.\n", age);
	printf("제 키는 %dcm이에요.", height);
	printf("제 키는 %5.2fm이에요.", (float)(height)/100);
	getch();
	return 0;
}
