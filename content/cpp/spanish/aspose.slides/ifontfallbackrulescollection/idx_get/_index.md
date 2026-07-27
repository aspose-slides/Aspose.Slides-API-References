---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la regla en el índice especificado. Solo lectura IFontFallBackRule.
type: docs
weight: 1
url: /es/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) método


Obtiene la regla en el índice especificado. Solo lectura [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Observaciones



```cpp
auto pres = MakeObject<Presentation>();
//Obtención de una colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Añadiendo varias reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recuperando el objeto de la primera regla en la colección
auto firstRule = rulesList->idx_get(0);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRule](../../ifontfallbackrule/)
* Clase [IFontFallBackRulesCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)