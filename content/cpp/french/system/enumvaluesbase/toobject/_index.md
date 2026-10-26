---
title: ToObject()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur entière non signée de 64 bits spécifiée en un membre d'énumération.
type: docs
weight: 40
url: /fr/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) méthode

Convertit la valeur entière non signée de 64 bits spécifiée en un membre d’énumération.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Le type d’énumération à retourner. |
| value | **uint64_t** | La valeur à convertir en un membre d’énumération. |

### Valeur de retour

Une instance de l’énumération définie sur la valeur.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) méthode

Convertit l’objet spécifié avec une valeur entière en un membre d’énumération.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Le type d’énumération à retourner. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | La valeur à convertir en un membre d’énumération. |

### Valeur de retour

Un objet d’énumération dont la valeur est la valeur.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [EnumValuesBase](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)