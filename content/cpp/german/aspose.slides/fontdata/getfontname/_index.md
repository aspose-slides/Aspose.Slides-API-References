---
title: GetFontName()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Schriftartnamen zurück und ersetzt die Theme-Referenz durch die tatsächlich verwendete Schriftart.
type: docs
weight: 27
url: /de/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) Methode


Gibt den Schriftartnamen zurück und ersetzt die Theme-Referenz durch die tatsächlich verwendete Schriftart.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) von dem der themenbasierte Schriftartname genommen werden soll. Es liegt am Aufrufer, einen korrekten Wert bereitzustellen. Siehe [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Rückgabewert

Schriftartname.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Klasse [FontData](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)