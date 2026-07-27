---
title: ReplaceFont()
second_title: Referencia de API de Aspose.Slides para C++
description: Reemplazar fuente en la presentación
type: docs
weight: 118
url: /es/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) método


Reemplazar fuente en la presentación

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Fuente de origen |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Fuente de destino |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) método


Reemplazar fuente en la presentación usando la información proporcionada en [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Información de sustitución de fuente |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) método


Reemplazar fuente en la presentación usando la información proporcionada en la colección de [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Colección de información de sustitución de fuente |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontData](../../ifontdata/)
* Clase [IFontsManager](../)
* Clase [IFontSubstRule](../../ifontsubstrule/)
* Clase [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)