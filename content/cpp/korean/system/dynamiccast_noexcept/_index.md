---
title: DynamicCast_noexcept()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오래된 구식 캐스트입니다. 향후 버전에서 제거될 예정입니다.
type: docs
weight: 2523
url: /ko/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) function


오래된 구식 캐스트입니다. 향후 버전에서 제거될 예정입니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | 소스 Exception 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const TFrom\& | 소스 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

## 비고


Exception 객체에 대해 dynamic cast를 수행합니다. 사용 중단:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) function


[SmartPtr](../smartptr/) 객체에 대해 dynamic cast를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 pointee 유형. |
| TFrom | 소스 pointee 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 소스 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용 중단:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) function


객체를 Exception 객체로 dynamic cast합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | [Object](../object/) 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 소스 포인터. |

### 반환값

캐스트가 허용되면 캐스트 결과를 반환하고, 그렇지 않으면 nullptr를 반환합니다.

사용 중단:   이전 호환성을 위해 남겨두었습니다. 대신 AsCast를 사용하십시오.

## 참조

* 클래스 [SmartPtr](../smartptr/)
* 클래스 [Object](../object/)
* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)