---
title: operator+()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 값과 지정된 Decimal 객체가 나타내는 값을 합한 값을 나타내는 Decimal 클래스의 새 인스턴스를 반환합니다.
type: docs
weight: 2185
url: /ko/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) 함수

지정된 값과 지정된 [Decimal](../decimal/) 객체가 나타내는 값의 합을 나타내는 [Decimal](../decimal/) 클래스의 새 인스턴스를 반환합니다.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const T\& | 첫 번째 피연산자 |
| d | const [Decimal](../decimal/)\& | 두 번째 피연산자를 나타내는 [Decimal](../decimal/) 객체에 대한 상수 참조 |

### 반환값

[Decimal](../decimal/) 클래스의 새 인스턴스로, **x**와 **d**가 나타내는 값의 합을 나타냅니다.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 함수

우측 위임자의 모든 콜백을 좌측 위임자 콜백 목록의 끝에 연결합니다.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | 콜백이 추가되는 위임자 |
| rhv | MulticastDelegate\<T\> | 콜백이 추가되는 위임자 |

### 반환값

좌측 값의 콜백과 그 다음에 우측 값의 콜백을 포함하는 위임자를 반환합니다.

## System::operator+(const T1\&, const Nullable\<T2\>\&) 함수

null이 아닌 값과 nullable 값을 합칩니다.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 왼쪽 피연산자 유형 |
| T2 | 오른쪽 피연산자 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| some | const T1\& | 왼쪽 피연산자 |
| other | const [Nullable](../nullable/)\<T2\>\& | 오른쪽 피연산자 |

### 반환값

합산 결과.

## System::operator+(T\&, const String\&) 함수

[String](../string/) 연결.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [String](../string/) 리터럴 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | T\& | 문자열에 연결할 리터럴 |
| right | const [String](../string/)\& | [String](../string/)를 연결 |

### 반환값

연결된 문자열.

## System::operator+(T\&, const String\&) 함수

[String](../string/) 연결.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [String](../string/) 포인터 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | T\& | [String](../string/) 포인터를 문자열에 연결 |
| right | const [String](../string/)\& | [String](../string/)를 연결 |

### 반환값

연결된 문자열.

## System::operator+(const char_t, const String\&) 함수

[String](../string/) 연결.

```cpp
String System::operator+(const char_t left, const String &right)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const char_t | 문자열에 연결할 문자 |
| right | const [String](../string/)\& | [String](../string/)를 연결 |

### 반환값

연결된 문자열.

## 참조

* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Class [String](../string/)
* Struct [IsStringLiteral](../isstringliteral/)
* Struct [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)