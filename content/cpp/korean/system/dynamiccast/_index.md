---
title: DynamicCast()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Exception 객체에 대한 동적 캐스트를 수행합니다.
type: docs
weight: 2536
url: /ko/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) 함수

Exception 객체에 대한 동적 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | 원본 Exception 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | 원본 포인터. |

### 반환 값

캐스트가 허용되는 경우 캐스트 결과.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) 함수

[SmartPtr](../smartptr/) 객체에 대한 동적 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 포인터가 가리키는 유형. |
| TFrom | 원본 포인터가 가리키는 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 원본 포인터. |

### 반환 값

캐스트가 허용되는 경우 캐스트 결과.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(SmartPtr\<TFrom\>) 함수

캐스트를 통해 박싱된 열거형을 언박스합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 enum 유형. |
| TFrom | 원본 포인터가 가리키는 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 데이터를 언박스할 객체에 대한 포인터. |

### 반환 값

언박스된 enum 값.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(std::nullptr_t) 함수

null 객체에 대한 동적 캐스트를 수행합니다.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 포인터가 가리키는 유형. |

### 반환 값

nullptr.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(TFrom\&) 함수

비포인터 객체에 대한 동적 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 유형. |
| TFrom | 원본 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | 원본 객체. |

### 반환 값

캐스트 결과.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(SmartPtr\<TFrom\>) 함수

Objects를 Exception 객체로 동적 캐스트합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 Exception 유형. |
| TFrom | [Object](../object/) 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 원본 포인터. |

### 반환 값

캐스트가 허용되는 경우 캐스트 결과.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## System::DynamicCast(TFrom) 함수

IntPtr에서 포인터로 동적 캐스트를 수행합니다.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| TTo | 대상 유형. |
| TFrom | 원본 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | 원본 IntPtr 값. |

### 반환 값

캐스트 결과.

Deprecated
:   이전 호환성을 위해 남겨 둔 것입니다. 대신 ExplicitCast를 사용하십시오.

## 참조

* 클래스 [SmartPtr](../smartptr/)
* 클래스 [Object](../object/)
* 구조체 [IsExceptionWrapper](../isexceptionwrapper/)
* 구조체 [CastResult](../castresult/)
* 구조체 [IsSmartPtr](../issmartptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)