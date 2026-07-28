---
title: FindAndReplaceText()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Znajduje i zamienia tekst w prezentacji przy podanym formacie
type: docs
weight: 40
url: /pl/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method

Znajduje i zamienia tekst w prezentacji przy podanym formacie

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Przeszukana prezentacja. |
| withMasters | **bool** | Określa, czy slajdy master powinny być przeszukane. |
| find | [System::String](../../../system/string/) | Wartość łańcucha do znalezienia. |
| replace | [System::String](../../../system/string/) | Wartość łańcucha do zastąpienia. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format zamiany fragmentu tekstu. Jeśli null, zostanie użyty format pierwszego znaku znalezionego ciągu. |

## Uwagi

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

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPresentation](../../../aspose.slides/ipresentation/)
* Klasa [String](../../../system/string/)
* Klasa [PortionFormat](../../../aspose.slides/portionformat/)
* Klasa [SlideUtil](../)
* Przestrzeń nazw [Aspose::Slides::Util](../../)
* Biblioteka [Aspose.Slides](../../../)