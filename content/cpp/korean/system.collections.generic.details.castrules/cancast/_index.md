---
title: CanCast()
second_title: Aspose.Slides for C++ API 참조
description: 캐스팅 가능성을 확인합니다.
type: docs
weight: 40
url: /ko/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

캐스팅 후 nullptr이 아닌 값이 반환되면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

캐스팅 후 nullptr이 아닌 값이 반환되면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

캐스팅 후 nullptr이 아닌 값이 반환되면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

항상 true를 반환합니다.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

캐스팅 후 nullptr이 아닌 값이 반환되면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

항상 true를 반환합니다.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

캐스팅 연산이 성공적으로 수행되면 true, 그렇지 않으면 false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) 함수

캐스팅 가능성을 확인합니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환값

항상 false를 반환합니다.

## 참조

* 구조체 [CastType](../casttype/)
* 네임스페이스 [System::Collections::Generic::Details::CastRules](../)
* 라이브러리 [Aspose.Slides](../../)