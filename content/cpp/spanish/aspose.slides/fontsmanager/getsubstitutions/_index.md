---
title: GetSubstitutions()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la información sobre las fuentes que serán sustituidas en la representación de la presentación.
type: docs
weight: 66
url: /es/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() method


Obtiene la información sobre las fuentes que serán sustituidas en la representación de la presentación.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### Valor de retorno

Colección de todas las sustituciones de fuentes [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method


Obtiene la información sobre las fuentes que serán sustituidas durante la representación de las diapositivas especificadas.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Una matriz de índices de diapositivas para los que se debe obtener la información de sustitución de fuentes, empezando desde 1. |

### Valor de retorno

Una colección de todas las sustituciones de fuentes ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) para las diapositivas especificadas.
## Observaciones




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Clase [FontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)