---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API Referencia
description: Megkeresi és helyettesíti a szöveget a bemutatóban a megadott formátummal
type: docs
weight: 40
url: /hu/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) metódus

Megkeresi és helyettesíti a szöveget a bemutatóban a megadott formátummal

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Átvizsgált bemutató. |
| withMasters | **bool** | Meghatározza, hogy a mester diákat is átvizsgálja-e. |
| find | [System::String](../../../system/string/) | A keresendő karakterlánc értéke. |
| replace | [System::String](../../../system/string/) | A helyettesítendő karakterlánc értéke. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | A szövegrész helyettesítéséhez használandó formátum. Ha null, akkor a megtalált karakterlánc első karakterének formátuma lesz használva. |

## Megjegyzések

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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPresentation](../../../aspose.slides/ipresentation/)
* Osztály [String](../../../system/string/)
* Osztály [PortionFormat](../../../aspose.slides/portionformat/)
* Osztály [SlideUtil](../)
* Névtér [Aspose::Slides::Util](../../)
* Könyvtár [Aspose.Slides](../../../)