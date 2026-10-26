---
title: GetSubstitutions()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la información sobre las fuentes que se reemplazarán en la representación de la presentación.
type: docs
weight: 66
url: /es/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() método


Obtiene la información sobre las fuentes que se reemplazarán en la representación de la presentación.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Valor devuelto

Colección de todas las sustituciones de fuentes [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) método


Obtiene la información sobre las fuentes que se reemplazarán durante la representación de las diapositivas especificadas.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Una matriz de índices de diapositivas para los que se debe obtener información de sustitución de fuentes, comenzando en 1. |

### Valor devuelto

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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)