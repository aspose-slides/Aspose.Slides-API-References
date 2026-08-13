---
title: IsNull()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 표현된 값이 nullptr인지 확인합니다.
type: docs
weight: 27
url: /ko/system.collections.generic.details.castrules/isnull/
---
## System::Collections::Generic::Details::CastRules::IsNull(T) 함수

표현된 값이 nullptr인지 확인합니다.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(T)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형입니다. |

### 반환 값

항상 false를 반환합니다.

## System::Collections::Generic::Details::CastRules::IsNull(SharedPtr\<T\>) 함수

표현된 값이 nullptr인지 확인합니다.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(SharedPtr<T> value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SharedPtr](../../system/sharedptr/)\<T\> | 검사해야 하는 값입니다. |

### 반환 값

값이 nullptr이면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::IsNull(Nullable\<T\>) 함수

표현된 값이 nullptr인지 확인합니다.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(Nullable<T> value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Nullable](../../system/nullable/)\<T\> | 검사해야 하는 값입니다. |

### 반환 값

값이 nullptr이면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [Nullable](../../system/nullable/)
* 네임스페이스 [System::Collections::Generic::Details::CastRules](../)
* 라이브러리 [Aspose.Slides](../../)