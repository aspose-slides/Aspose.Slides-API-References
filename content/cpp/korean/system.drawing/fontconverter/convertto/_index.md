---
title: ConvertTo()
second_title: Aspose.Slides for C++ API 참조
description: 객체를 특정 타입으로 변환합니다.
type: docs
weight: 14
url: /ko/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) 메서드

객체를 특정 타입으로 변환합니다.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 객체를 변환할 때 사용할 문화. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 변환할 객체. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | 변환할 타입. |

### 반환값

변환된 객체.

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [FontConverter](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)