# 스케줄

---

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### BlockQuote

- 주석은 >로 표현 주석 내 주석은 >> 2개를 씀
  > This is a first blockquote
  >
  > > This is a second blockquote
  >
  > This is a first blockquote

### 목록 (LIST)

#### 1) 순서가 있는 목록

1. 목록1
   1. 목록 1_1
   2. 목록 1_2
2. 목록2
   1. 목록2_1
   2. 목록2_2
3. 목록3
4. 목록4

#### 2) 순서가 없는 목록

- 목록 1
  - 목록 1_1
  - 목록 1_2
- 목록 2
  - 목록 2_1
  - 목록 2_2
- 목록3

### 표만들기

- |(vertical bar) : 테이블 표현
- : 정렬, 앞뒤로 쓰면 가운데 정렬, 앞쪽에 쓰면 왼쪽 정렬, 뒤에 쓰면 오른쪽 정렬
- (---) 헤더와 셀 구분

| 이름   | 주소   | 전화번호      |
| :----- | :----- | :------------ |
| 홍길동 | 서울시 | 02-1234-23456 |
| 여진구 | 경기도 | 031-2523-5233 |

### 코드(code)

#### 1) 인라인 코드(inline code)

- 백틱(\`)으로 강조할 내용을 감싼다.
  repository에서 프로젝트의 설명을 부여해줄때 `README.md`을 사용한다.

#### 2) 블럭코드(block code)

- 백틱(`) 3개로 html, css, java등 코드를 작성할 때 사용한다.

```java
  public static void main(String args){
      System.out.println("Hello Java");
  }
```
