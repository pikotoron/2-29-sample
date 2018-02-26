?に何かを入れれば動くというヒントのつもりです。見づらくてごめんなさい。



### 練習1
```
#include <stdio.h>

int main(void)
{
  int i; //ループ用カウント変数

  for(i=0; i<100; i++) {
    printf("Hello World!\n");
  }

  return 0;
}
```

### 練習2
```
#include <stdio.h>

int main(void)
{
  int i,j; //ループ用カウント変数

  for( ? ;  ?  ; i++) {
    for( ? ;  ?  ; j++) {
      printf("%d ? ",i*j);
    }
    printf("\n");
  }

  return 0;
}
```

### 練習3
```
#include <stdio.h>

int main(void)
{
  int age;

  printf("あなたの年齢を教えてください。\n");
  scanf("%d",&age);

  while (  ?  ) {
    printf("正しく年齢を入力してください。\n");
    scanf("%d",&age);
    if (age >= 0) {
        ?  ;
    }
  }

  printf("あなたの年齢は%d歳ですね\n",age);

  return 0;
}
```
