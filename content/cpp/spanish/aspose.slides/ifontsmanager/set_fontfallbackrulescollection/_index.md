---
title: set_FontFallBackRulesCollection()
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de fallback. Escribe IFontFallBackRulesCollection.
type: docs
weight: 40
url: /es/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) método


Representa la colección de reglas FontFallBack de un usuario para la gestión de colecciones de fuentes para sustituciones adecuadas mediante la funcionalidad de fallback. Escribe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Comentarios


```cpp
auto pres = MakeObject<Presentation>();
// Obtención de una colección de reglas vacía o preinicializada del FontsManager
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Clase [IFontsManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)