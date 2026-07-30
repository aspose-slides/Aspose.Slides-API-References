---
title: GetFontName()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací název písma, nahrazujíc odkaz na téma skutečným použitým písmem.
type: docs
weight: 27
url: /cs/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) metoda

Vrací název písma, nahrazující odkaz na téma skutečným použitým písmem.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) ze kterého by měl být převzat název písma v tématu. Je na volajícím, aby poskytl správnou hodnotu. Viz [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Návratová hodnota

Název písma.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [String](../../../system/string/)
* třída [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* třída [FontData](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)