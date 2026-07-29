---
title: FindAndReplaceText()
second_title: Aspose.Slides för C++ API-referens
description: Söker och ersätter text i presentationen med angivet format
type: docs
weight: 40
url: /sv/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) metod


Söker och ersätter text i presentationen med angivet format

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Skannad presentation. |
| withMasters | **bool** | Bestämmer om masterbilder ska genomsökas. |
| find | [System::String](../../../system/string/) | Strängvärde att hitta. |
| replace | [System::String](../../../system/string/) | Strängvärde att ersätta. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format för att ersätta textdel. Om null används formatet för det första tecknet i den hittade strängen |
## Anmärkningar




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




## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPresentation](../../../aspose.slides/ipresentation/)
* Klass [String](../../../system/string/)
* Klass [PortionFormat](../../../aspose.slides/portionformat/)
* Klass [SlideUtil](../)
* Namnrymd [Aspose::Slides::Util](../../)
* Bibliotek [Aspose.Slides](../../../)