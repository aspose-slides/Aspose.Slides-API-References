---
title: get_FontFallBackRulesCollection()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de reserva. Lea IFontFallBackRulesCollection.
type: docs
weight: 27
url: /es/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() método

Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de reserva. Lea [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Observaciones



```cpp
auto pres = MakeObject<Presentation>();
// Obtención de la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Añadiendo reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// o
// inicialización de una nueva instancia de la colección de reglas
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Añadiendo reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// y reemplazo de la colección existente por la nueva en FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Clase [FontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)