---
title: set_FontFallBackRulesCollection()
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes y sustituciones adecuadas mediante la funcionalidad de reserva. Escriba IFontFallBackRulesCollection.
type: docs
weight: 40
url: /es/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) método

Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes y sustituciones adecuadas mediante la funcionalidad de reserva. Escriba [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Observaciones



```cpp
auto pres = MakeObject<Presentation>();
// Obtención de la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// agregando reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// o
// inicialización de una nueva instancia de la colección de reglas
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// agregando reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// y reemplazo de la colección existente por la nueva en FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Clase [FontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)