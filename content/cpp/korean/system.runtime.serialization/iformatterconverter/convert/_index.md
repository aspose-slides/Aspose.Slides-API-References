---
title: Convert()
second_title: Aspose.Slides for C++ API 참조
description: RTTI 정보.
type: docs
weight: 1
url: /ko/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

RTTI 정보.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 변환될 객체. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 값이 변환될 [System::TypeInfo](../../../system/typeinfo/). |

### 반환 값

변환된 값.

## 비고

값을 지정된 [System::TypeInfo](../../../system/typeinfo/)로 변환합니다.

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

값을 지정된 [System::TypeCode](../../../system/typecode/)로 변환합니다.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 변환될 객체. |
| typeCode | [TypeCode](../../../system/typecode/) | 값이 변환될 [System::TypeCode](../../../system/typecode/). |

### 반환 값

변환된 값.

## 참조

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)