---
title: EnumValuesBase
second_title: Référence de l'API Aspose.Slides pour C++
description: Une classe de base pour une classe qui représente les méta informations d'un type d'énumération.
type: docs
weight: 807
url: /fr/system/enumvaluesbase/
---
## EnumValuesBase classe

Une classe de base pour une classe qui représente les meta informations d'un type d'enumeration.

```cpp
class EnumValuesBase
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Récupère un tableau des noms des constantes d'une énumération spécifiée. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Renvoie le type sous-jacent de l'énumération spécifiée. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Renvoie un tableau contenant toutes les valeurs du type d'énumération spécifié. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Renvoie un objet qui représente la valeur d'une constante d'énumération du type d'énumération spécifié avec le nom spécifié. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Convertit la valeur entière non signée 64 bits spécifiée en un membre d'énumération. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Convertit l'objet spécifié avec une valeur entière en un membre d'énumération. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)