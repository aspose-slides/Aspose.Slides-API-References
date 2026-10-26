---
title: get_FontFallBackRulesCollection()
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de fallback. Lea IFontFallBackRulesCollection.
type: docs
weight: 27
url: /es/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() método

Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones correctas mediante la funcionalidad de fallback. Lea [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Observaciones



```cpp
auto pres = MakeObject<Presentation>();
// Obtener la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// añadiendo reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// o
// inicialización de una nueva instancia de la colección de reglas
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// añadiendo reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// y reemplazando la colección existente por la nueva en FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Clase [IFontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)