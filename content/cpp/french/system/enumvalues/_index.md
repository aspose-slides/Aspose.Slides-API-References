---
title: EnumValues
second_title: Référence API Aspose.Slides pour C++
description: Fournit des informations méta sur les constantes d'énumération du type E.
type: docs
weight: 794
url: /fr/system/enumvalues/
---
## EnumValues classe

Fournit des informations méta sur les constantes d'énumération du type d'énumération **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| E | Le type d'énumération |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Construit une instance. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Renvoie un tableau contenant tous les noms de l'énumération **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Récupère un tableau des noms des constantes d'une énumération spécifiée. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Renvoie le type sous-jacent de l'énumération spécifiée. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Renvoie le type sous-jacent de l'énumération spécifiée. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Renvoie la valeur encapsulée de la constante d'énumération avec le nom spécifié. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Renvoie la valeur encapsulée de la constante d'énumération avec la valeur spécifiée. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Renvoie un tableau contenant toutes les valeurs de l'énumération **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Renvoie un tableau contenant toutes les valeurs du type d'énumération spécifié. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Renvoie un objet qui représente la valeur d'une constante d'énumération du type d'énumération spécifié avec le nom spécifié. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Convertit la valeur entière non signée 64 bits spécifiée en un membre d'énumération. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Convertit l'objet spécifié avec une valeur entière en un membre d'énumération. |
| virtual  [~EnumValues](./~enumvalues/)() | Destructeur. |

## Voir aussi

* Classe [EnumValuesBase](../enumvaluesbase/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)