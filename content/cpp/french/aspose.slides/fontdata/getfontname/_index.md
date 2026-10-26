---
title: GetFontName()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Renvoie le nom de la police, en remplaçant la référence du thème par une police réellement utilisée.
type: docs
weight: 27
url: /fr/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method

Renvoie le nom de la police, en remplaçant la référence du thème par une police réellement utilisée.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) à partir duquel le nom de police thématisé doit être récupéré. Il appartient à l'appelant de fournir une valeur correcte. Voir [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Valeur de retour

Nom de la police.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Class [FontData](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)