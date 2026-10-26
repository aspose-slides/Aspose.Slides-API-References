---
title: StaticCast()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartPtr 객체에 대해 정적 캐스팅을 수행합니다.
type: docs
weight: 2562
url: /ko/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) 함수


[SmartPtr](../smartptr/) 객체에 대해 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 유형. |
| TFrom | 원본 pointee 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 원본 포인터. |

### 반환 값

캐스팅이 허용되는 경우 캐스팅 결과.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCast(WeakPtr\<TFrom\> const\&) 함수


[WeakPtr](../weakptr/) 객체에 대해 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 유형. |
| TFrom | 원본 pointee 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 원본 포인터. |

### 반환 값

캐스팅이 허용되는 경우 캐스팅 결과.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCast(std::nullptr_t) 함수


null 객체에 대해 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 유형. |

### 반환 값

nullptr.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCast(TFrom) 함수


산술형에 대한 특수화.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) 함수


[String](../string/)에서 [String](../string/)로 캐스팅을 처리합니다.

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) 함수


산술형에 대한 특수화.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) 함수


포인터가 아닌 객체에 대해 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 유형. |
| TFrom | 원본 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const TFrom\& | 원본 객체. |

### 반환 값

캐스팅이 허용되는 경우 캐스팅 결과.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCast(const TFrom\&) 함수


Exception 객체에 대해 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | 원본 Exception 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const TFrom\& | 원본 포인터. |

### 반환 값

캐스팅이 허용되는 경우 캐스팅 결과.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::StaticCast(SmartPtr\<TFrom\>) 함수


객체를 Exception 객체로 정적 캐스팅을 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | [Object](../object/) 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 원본 포인터. |

### 반환 값

캐스팅이 허용되는 경우 캐스팅 결과.

사용 중단
:   이전 호환성을 위해 남겨둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## 또 보기

* 클래스 [SmartPtr](../smartptr/)
* 클래스 [WeakPtr](../weakptr/)
* 클래스 [String](../string/)
* 클래스 [Object](../object/)
* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 구조체 [CastResult](../castresult/)
* 구조체 [IsSmartPtr](../issmartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)