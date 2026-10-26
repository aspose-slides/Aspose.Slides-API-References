---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API Referentie
description: Zoekt en vervangt tekst in de presentatie met het opgegeven formaat
type: docs
weight: 40
url: /nl/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) methode


Zoekt en vervangt tekst in de presentatie met het opgegeven formaat

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Gescande presentatie. |
| withMasters | **bool** | Bepaalt of master-dia's moeten worden gescand. |
| find | [System::String](../../../system/string/) | Te zoeken tekenreeks. |
| replace | [System::String](../../../system/string/) | Te vervangen tekenreeks. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Formaat voor het vervangen van tekstgedeelte. Als null wordt het formaat van het eerste teken van de gevonden tekenreeks gebruikt |
## Opmerkingen




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




## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentation](../../../aspose.slides/ipresentation/)
* Klasse [String](../../../system/string/)
* Klasse [PortionFormat](../../../aspose.slides/portionformat/)
* Klasse [SlideUtil](../)
* Naamruimte [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)