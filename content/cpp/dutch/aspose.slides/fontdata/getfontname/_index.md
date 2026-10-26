---
title: GetFontName()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de naam van het lettertype, waarbij de themaverwijzing wordt vervangen door een daadwerkelijk gebruikt lettertype.
type: docs
weight: 27
url: /nl/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method

Retourneert de naam van het lettertype, waarbij de themaverwijzing wordt vervangen door een daadwerkelijk gebruikt lettertype.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) waaruit de thematische lettertype naam moet worden genomen. Het is aan de aanroeper om een correcte waarde te leveren. Zie [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Retourwaarde

Lettertype-naam.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Klasse [FontData](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)