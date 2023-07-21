# 과제 주제 : 파이썬 실습


## 🖥️ 엘리스 은행
엘리스 은행은 고객을 위하여 동전교환 무인기기를 제공하고 있습니다. 고객들의 요청으로 10원, 50원, 100원, 500원으로 n원어치 동전교환을 할 때 몇 가지 경우의 수가 있는지 표시해주려고 합니다.
<br>

다음 지시사항을 따라서 10원, 50원, 100원, 500원의 4가지 동전을 사용해서 주어진 금액의 거스름돈을 줄 수 있는 모든 경우의 수를 반환하는 프로그램을 작성해 봅시다.
<br>
<br>

## 👉 지시사항
1. 교환가능 금액(money)은 10원보다 크고, 100,000원보다 작습니다.
2. 👆 위 교환가능 금액 이외의 값이 입력으로 들어오면 0을 반환합니다.
4. count 배열을 반환하여 거스름돈을 줄 수 있는 모든 경우의 수를 반환합니다.
5. 교환하려는 금액은 사용자에게 문자열로 입력 받아 처리합니다.
6. 모든 동전은 무한하게 제공됩니다.

<br>
<br>


### 입력 예시
```python
1000
```

### 출력 예시
```python
158
```

### Tips!
- 기본적으로 주어진 변수를 삭제하거나 지시사항에서 제시한 변수 이름을 사용하지 않으면 채점 시 오류가 발생할 수 있으니 유의하시기 바랍니다.
- [N번째 동전까지 사용해서 M원을 만드는 경우의 수 = (N-1)번째 동전까지 사용해서 M원을 만드는 경우의 수 + N번째 동전까지 사용해서 (M-N번째 동전)원을 만드는 경우의 수]로 접근해주세요.

<br>
<br>

## ⚙️ 기술 스택
#### PYTHON

<br>
<br>

## 📌 기획 의도 및 학습 내용
- 컴퓨팅적 사고력을 기를 수 있다.
- 파이썬 개념을 적용해볼 수 있다.
- [N번째 동전까지 사용해서 M원을 만드는 경우의 수 = (N-1)번째 동전까지 사용해서 M원을 만드는 경우의 수 + N번째 동전까지 사용해서 (M-N번째 동전)원을 만드는 경우의 수]를 이해하며 프로그램을 작성할 수 있다.


