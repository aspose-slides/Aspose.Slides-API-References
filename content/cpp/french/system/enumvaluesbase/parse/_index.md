---
title: Parse()
second_title: Référence API Aspose.Slides for C++
description: Renvoie un objet qui représente la valeur d'une constante d'énumération du type d'énumération spécifié avec le nom spécifié.
type: docs
weight: 27
url: /fr/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) méthode

Renvoie un objet qui représente la valeur d'une constante d'énumération du type d'énumération spécifié avec le nom spécifié.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | L'objet [TypeInfo](../../typeinfo/) représentant le type de la valeur d'énumération à retourner |
| str | const [String](../../string/)\& | Le nom de la constante d'énumération |
| ignoreCase | **bool** | Spécifie si la casse doit être ignorée lors de l'interprétation du nom de la constante d'énumération |

### Valeur de retour

Un objet qui représente la valeur de la constante d'énumération dont le nom est spécifié dans **str**.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [EnumValuesBase](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)