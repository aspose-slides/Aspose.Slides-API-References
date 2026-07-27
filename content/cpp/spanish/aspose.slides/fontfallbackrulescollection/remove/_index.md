---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la primera aparición de una regla FallBack específica de la colección.
type: docs
weight: 53
url: /es/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) método

Elimina la primera aparición de una regla FallBack específica de la colección.

```cpp
void Aspense::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | La regla a eliminar de la colección. |
## Observaciones

```cpp
auto pres = MakeObject<Presentation>();
//Obteniendo la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Agregando varias reglas a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Obteniendo el objeto de la primera regla en la colección
auto firstRule = rulesList->idx_get(0);
//Eliminando
rulesList->Remove(firstRule);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRule](../../ifontfallbackrule/)
* Clase [FontFallBackRulesCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)