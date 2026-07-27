---
title: GetFontName()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el nombre de la fuente, reemplazando la referencia del tema con una fuente real utilizada.
type: docs
weight: 27
url: /es/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method


Devuelve el nombre de la fuente, reemplazando la referencia del tema con una fuente real utilizada.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) desde el cual se debe tomar el nombre de la fuente tematizada. Depende del llamador proporcionar un valor correcto. Ver [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Valor de retorno

Nombre de la fuente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Clase [FontData](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)