---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API Reference
description: Finds and replaces text in presentation with given format
type: docs
weight: 27
url: /aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method


Finds and replaces text in presentation with given format

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Scanned presentation. |
| withMasters | **bool** | Determines whether master slides should be scanned. |
| find | [System::String](../../../system/string/) | String value to find. |
| replace | [System::String](../../../system/string/) | String value to replace. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format for replacing text portion. If null then will be used format of the first character of the found string |
## Remarks




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




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [PortionFormat](../../../aspose.slides/portionformat/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)