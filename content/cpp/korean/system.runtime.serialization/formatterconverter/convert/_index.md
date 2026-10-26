---
title: Convert()
second_title: Aspose.Slides for C++ API 참조
description: "값을 주어진 System::TypeInfo 로 변환합니다."
type: docs
weight: 1
url: /ko/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) 메서드

값을 주어진 [System::TypeInfo](../../../system/typeinfo/)로 변환합니다.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 변환할 객체. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 값이 변환될 [System::TypeInfo](../../../system/typeinfo/). |

### 반환값

변환된 값.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) 메서드

값을 주어진 [System::TypeCode](../../../system/typecode/)로 변환합니다.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 변환할 객체. |
| typeCode | [TypeCode](../../../system/typecode/) | 값이 변환될 [System::TypeCode](../../../system/typecode/). |

### 반환값

변환된 값.

## 참고

* 열거형 [TypeCode](../../../system/typecode/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [FormatterConverter](../)
* 네임스페이스 [System::Runtime::Serialization](../../)
* 라이브러리 [Aspose.Slides](../../../)