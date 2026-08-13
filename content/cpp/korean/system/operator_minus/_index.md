---
title: operator-()
second_title: Aspose.Slides for C++ API 참조
description: 두 요일 사이의 일 수를 계산합니다.
type: docs
weight: 2172
url: /ko/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) 함수

두 요일 사이의 일 수를 계산합니다.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### 반환 값

요일 **a**와 **b** 사이의 일 수; *goes*가 **** 후에 오는 경우 반환값은 음수입니다.

## System::operator-(const T\&, const Decimal\&) 함수

새로운 [Decimal](../decimal/) 클래스 인스턴스를 반환합니다. 이 인스턴스는 지정된 [Decimal](../decimal/) 객체가 나타내는 값에서 지정된 값을 뺀 결과 값을 나타냅니다.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const T\& | The value to subtract from |
| d | const [Decimal](../decimal/)\& | The [Decimal](../decimal/) object representing the subtracted value |

### 반환 값

새로운 [Decimal](../decimal/) 클래스 인스턴스를 반환합니다. 이 인스턴스는 **d**가 나타내는 값을 **x**에서 뺀 결과 값을 나타냅니다.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 함수

왼쪽 위임 콜백 목록의 끝에서 오른쪽 위임의 모든 콜백을 분리합니다.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate from which callbacks will be removed. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks will be removed. |

### 반환 값

왼쪽 값의 콜백을 포함하지만 오른쪽 값의 콜백은 제외한 위임을 반환합니다.

## System::operator-(const T1\&, const Nullable\<T2\>\&) 함수

널이 아닌 값과 널 허용 값을 뺍니다.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### 반환 값

뺄셈 결과.

## 또 보기

* Enum [DayOfWeek](../dayofweek/)
* 클래스 [Decimal](../decimal/)
* 클래스 [Nullable](../nullable/)
* 네임스페이스 [System](../)
* Library [Aspose.Slides](../../)