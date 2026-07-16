---
title: GetValueOf()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur encapsulée de la constante d'énumération avec le nom spécifié.
type: docs
weight: 53
url: /fr/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String&, bool) const méthode

Renvoie la valeur encapsulée de la constante d'énumération avec le nom spécifié.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | Le nom de la constante d'énumération |
| ignoreCase | **bool** | Spécifie si la casse doit être ignorée lors de l'interprétation du nom de la constante d'énumération |

### Valeur de retour

Une valeur encapsulée de la constante d'énumération dont le nom est spécifié dans **str**.

## EnumValues::GetValueOf(long) const méthode

Renvoie la valeur encapsulée de la constante d'énumération avec la valeur spécifiée.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| val | long | La valeur de la constante d'énumération |

### Valeur de retour

Une valeur encapsulée de la constante d'énumération dont la valeur est spécifiée dans **str**.

## Voir également

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [String](../../string/)
* Classe [EnumValues](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)