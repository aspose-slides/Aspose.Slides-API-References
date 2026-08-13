---
title: ConvertToInvariantString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체를 불변 문자열로 변환합니다.
type: docs
weight: 66
url: /ko/system.componentmodel/typeconverter/converttoinvariantstring/
---
## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<System::Object\>\&) method

객체를 불변 문자열로 변환합니다.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<System::Object> &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 변환할. |

### 반환 값

변환된 객체.

## TypeConverter::ConvertToInvariantString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) method

객체를 불변 문자열로 변환합니다.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToInvariantString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) 변환할. |

### 반환 값

변환된 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeConverter](../)
* 클래스 [ITypeDescriptorContext](../../itypedescriptorcontext/)
* 네임스페이스 [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)