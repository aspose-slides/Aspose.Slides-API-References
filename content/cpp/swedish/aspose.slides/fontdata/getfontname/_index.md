---
title: GetFontName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar typsnittsnamnet, ersätter temareferensen med ett faktiskt använt teckensnitt.
type: docs
weight: 27
url: /sv/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method

Returnerar typsnittsnamnet och ersätter temareferensen med ett faktiskt använt teckensnitt.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) från vilken temabaserat typsnittsnamn bör tas. Det är upp till anroparen att tillhandahålla ett korrekt värde. Se [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Returvärde

Typsnittsnamn.

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Klass [FontData](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)