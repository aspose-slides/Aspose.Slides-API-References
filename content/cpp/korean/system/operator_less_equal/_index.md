---
title: operator<=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 2107
url: /ko/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) 함수




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) 함수




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) 함수


항상 false를 반환합니다.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) 함수


지정된 [Nullable](../nullable/) 객체가 나타내는 값에 [operator<=()](./)를 적용하여, 지정된 값이 그 값보다 작거나 같은지 여부를 결정합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 비교값의 형식 |
| T2 | 두 번째 비교값을 나타내는 [Nullable](../nullable/) 객체의 기본 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| some | const T1\& | 첫 번째 비교값으로 사용할 값에 대한 상수 참조 |
| other | const [Nullable](../nullable/)\<T2\>\& | 두 번째 비교값으로 사용할 값을 나타내는 [Nullable](../nullable/) 객체에 대한 상수 참조 |

### 반환 값

첫 번째 비교값이 두 번째 비교값보다 작거나 같으면 true, 그렇지 않으면 false

## System::operator<=(std::nullptr_t, TimeSpan) 함수




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## 참조

* 클래스 [DateTime](../datetime/)
* 클래스 [DateTimeOffset](../datetimeoffset/)
* 클래스 [Nullable](../nullable/)
* 클래스 [TimeSpan](../timespan/)
* 구조체 [IsNullable](../isnullable/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)