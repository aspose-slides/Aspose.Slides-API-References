---
title: GetFontName()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a betűtípus nevét, a téma hivatkozást egy ténylegesen használt betűtípusra cserélve.
type: docs
weight: 27
url: /hu/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) metódus


Visszaadja a betűtípus nevét, a téma hivatkozást egy ténylegesen használt betűtípusra cserélve.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) amelyből a témához tartozó betűtípus nevet kell venni. A hívónak kell biztosítania a megfelelő értéket. Lásd [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Visszatérési érték

Betűtípus neve.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Class [FontData](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)