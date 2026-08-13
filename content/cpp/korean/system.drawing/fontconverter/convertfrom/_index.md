---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체를 변환합니다.
type: docs
weight: 1
url: /ko/system.drawing/fontconverter/convertfrom/
---
## FontConverter::ConvertFrom(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) 메서드

객체를 변환합니다.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertFrom(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 객체를 변환할 때 사용할 문화. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 변환할 객체. |

### 반환 값

변환된 객체.

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [FontConverter](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)