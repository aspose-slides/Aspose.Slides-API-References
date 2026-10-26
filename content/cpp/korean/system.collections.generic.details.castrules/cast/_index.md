---
title: Cast()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 소스 유형을 결과 유형으로 캐스팅합니다. 소스와 결과 유형이 동일할 때 사용됩니다.
type: docs
weight: 14
url: /ko/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 및 결과 유형이 동일할 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 유형을 정적으로 캐스팅할 수 있을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 유형이 동일하지 않고 소스 유형을 정적으로 캐스팅할 수 없을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 유형이 [Nullable](../../system/nullable/) 클래스 인스턴스로 박싱되고 있을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 유형이 [Nullable](../../system/nullable/) 클래스 인스턴스로부터 언박싱되고 있을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 유형이 [Object](../../system/object/) 클래스 인스턴스로 박싱되고 있을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 소스 유형이 [Object](../../system/object/) 클래스 인스턴스로부터 언박싱되고 있을 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## System::Collections::Generic::Details::CastRules::Cast(Source) 함수

소스 유형을 결과 유형으로 캐스팅합니다. 캐스팅이 유효하지 않거나 변환이 명시적일 때 사용됩니다.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Source | 소스 유형. |
| Result | 결과 유형. |

### 반환 값

캐스팅 결과.

## 또 보기

* 구조체 [CastType](../casttype/)
* 네임스페이스 [System::Collections::Generic::Details::CastRules](../)
* 라이브러리 [Aspose.Slides](../../)