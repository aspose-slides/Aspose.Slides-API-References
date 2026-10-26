---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartPtr 객체에 static 캐스트를 수행합니다.
type: docs
weight: 2549
url: /ko/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) 함수


[SmartPtr](../smartptr/) 객체에 대한 static 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 타입. |
| TFrom | 원본 pointee 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 원본 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용되지 않음
:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) 함수


[WeakPtr](../weakptr/) 객체에 대한 static 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 타입. |
| TFrom | 원본 pointee 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 원본 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용되지 않음
:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## System::StaticCast_noexcept(const TFrom\&) 함수


Exception 객체에 대한 static 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 타입. |
| TFrom | 원본 Exception 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const TFrom\& | 원본 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용되지 않음
:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) 함수


Objects를 Exception 객체로 static 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 타입. |
| TFrom | [Object](../object/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 원본 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용되지 않음
:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## 또한 보기

* 클래스 [SmartPtr](../smartptr/)
* 클래스 [WeakPtr](../weakptr/)
* 클래스 [Object](../object/)
* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 구조체 [CastResult](../castresult/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)