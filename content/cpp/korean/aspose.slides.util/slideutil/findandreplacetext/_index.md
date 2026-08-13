---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에서 지정된 형식으로 텍스트를 찾고 교체합니다
type: docs
weight: 40
url: /ko/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method

프레젠테이션에서 지정된 형식으로 텍스트를 찾고 교체합니다

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 스캔된 프레젠테이션입니다. |
| withMasters | **bool** | 마스터 슬라이드도 스캔할지 여부를 결정합니다. |
| find | [System::String](../../../system/string/) | 찾을 문자열 값입니다. |
| replace | [System::String](../../../system/string/) | 교체할 문자열 값입니다. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | 텍스트 부분을 교체할 형식입니다. null인 경우 찾은 문자열의 첫 문자 형식이 사용됩니다. |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [PortionFormat](../../../aspose.slides/portionformat/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)