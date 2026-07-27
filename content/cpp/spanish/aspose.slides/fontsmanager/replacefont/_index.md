---
title: ReplaceFont()
second_title: Referencia de la API de Aspose.Slides para C++
description: Reemplazar fuente en la presentación
type: docs
weight: 118
url: /es/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) método

Reemplazar fuente en la presentación

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Fuente de origen |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Fuente de destino |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) método

Reemplazar fuente en la presentación usando la información provista en [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Información de sustitución de fuentes |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) método

Reemplazar fuente en la presentación usando la información provista en la colección de [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Colección de reglas de sustitución de fuentes |

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontData](../../ifontdata/)
* Clase [FontsManager](../)
* Clase [IFontSubstRule](../../ifontsubstrule/)
* Clase [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)