---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체를 특정 유형으로 변환합니다.
type: docs
weight: 53
url: /ko/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 메서드

객체를 특정 유형으로 변환합니다.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 변환할. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 변환할 유형. |

### 반환값

변환된 객체.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 메서드

객체를 특정 유형으로 변환합니다.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 객체를 변환할 때 사용할 문화. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 변환할. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 변환할 유형. |

### 반환값

변환된 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [TypeConverter](../)
* 클래스 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)