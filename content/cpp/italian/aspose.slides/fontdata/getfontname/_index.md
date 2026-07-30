---
title: GetFontName()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il nome del font, sostituendo il riferimento al tema con un vero font utilizzato.
type: docs
weight: 27
url: /it/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) metodo

Restituisce il nome del font, sostituendo il riferimento al tema con un vero font utilizzato.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) da cui dovrebbe essere preso il nome del font tematico. Spetta al chiamante fornire un valore corretto. Vedi [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Valore di ritorno

Nome del font.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Classe [FontData](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)