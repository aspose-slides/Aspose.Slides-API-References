---
title: ConvertFrom()
second_title: Aspose.Slides for C++ API 참조
description: 객체를 변환합니다.
type: docs
weight: 14
url: /ko/system.drawing/imageformatconverter/convertfrom/
---
## ImageFormatConverter::ConvertFrom(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&) 메서드


객체를 변환합니다.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertFrom(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) 변환 컨텍스트 정보. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 객체를 변환할 때 사용할 문화. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) 변환할 대상. |

### 반환값

변환된 객체.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [ImageFormatConverter](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)