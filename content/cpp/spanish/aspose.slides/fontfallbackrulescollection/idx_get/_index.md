---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la regla en el índice especificado. Solo lectura IFontFallBackRule.
type: docs
weight: 66
url: /es/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) método

Obtiene la regla en el índice especificado. Solo lectura [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Observaciones


```cpp
auto pres = MakeObject<Presentation>();
//Obteniendo la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Agregando varias reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recuperando el objeto de la primera regla en la colección
auto firstRule = rulesList->idx_get(0);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRule](../../ifontfallbackrule/)
* Clase [FontFallBackRulesCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)