---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega una regla FallBack especificada al final de la colección.
type: docs
weight: 40
url: /es/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Agrega una regla FallBack especificada al final de la colección.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Regla especificada para agregar |
## Observaciones

```cpp
auto pres = MakeObject<Presentation>();
//Obtención de la colección de reglas vacía o preinicializada del FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Agregar una nueva regla a la colección
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IFontFallBackRule](../../ifontfallbackrule/)
* Clase [FontFallBackRulesCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)