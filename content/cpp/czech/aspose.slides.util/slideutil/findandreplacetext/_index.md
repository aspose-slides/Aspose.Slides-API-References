---
title: FindAndReplaceText()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vyhledá a nahradí text v prezentaci s daným formátem
type: docs
weight: 40
url: /cs/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method

Vyhledá a nahradí text v prezentaci s daným formátem

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Prohledaná prezentace. |
| withMasters | **bool** | Určuje, zda mají být prohledány hlavní snímky. |
| find | [System::String](../../../system/string/) | Řetězcová hodnota k vyhledání. |
| replace | [System::String](../../../system/string/) | Řetězcová hodnota k nahrazení. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Formát pro nahrazení části textu. Pokud je null, bude použit formát prvního znaku nalezeného řetězce. |

## Poznámky

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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [PortionFormat](../../../aspose.slides/portionformat/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)