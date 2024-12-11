#include <stdio.h>
#include <stdlib.h> // atoi 함수를 사용하기 위해 포함

int main(int argc, char* argv[]) {
    // 인자가 3개인지 확인 (프로그램 이름 + 두 개의 숫자)
    if (argc != 3) {
        printf("Usage: %s <num1> <num2>\n", argv[0]);
        return 1; // 잘못된 인자 수
    }

    // 문자열을 정수로 변환
    int num1 = atoi(argv[1]);
    int num2 = atoi(argv[2]);

    // 사칙연산 결과 출력
    printf("덧셈: %d + %d = %d\n", num1, num2, num1 + num2);
    printf("뺄셈: %d - %d = %d\n", num1, num2, num1 - num2);
    printf("곱셈: %d * %d = %d\n", num1, num2, num1 * num2);

    // 나눗셈은 0으로 나누는 경우를 체크
    if (num2 != 0) {
        printf("나눗셈: %d / %d = %.2f\n", num1, num2, (float)num1 / num2);
    }
    else {
        printf("나눗셈: 0으로 나눌 수 없습니다.\n");
    }

    return 0; // 프로그램 정상 종료
}
