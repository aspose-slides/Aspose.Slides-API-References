---
title: operator<()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 2094
url: /ko/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) function


항상 false를 반환합니다.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) function


이 두 값에 [operator<()](./)를 적용하여 지정된 [Nullable](../nullable/) 객체가 나타내는 값보다 지정된 값이 더 작은지 판단합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 비교값의 형식 |
| T2 | [Nullable](../nullable/) 객체가 두 번째 비교값을 나타내는 기본 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| some | const T1\& | 첫 번째 비교값으로 사용할 값에 대한 상수 참조 |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) 객체에 대한 상수 참조이며, 해당 값은 두 번째 비교값으로 사용됩니다. |

### 반환 값

첫 번째 비교값이 두 번째 비교값보다 작으면 true, 그렇지 않으면 false

## System::operator<(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## 참고

* 클래스 [DateTime](../datetime/)
* 클래스 [DateTimeOffset](../datetimeoffset/)
* 클래스 [Nullable](../nullable/)
* 클래스 [TimeSpan](../timespan/)
* 구조체 [IsNullable](../isnullable/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)