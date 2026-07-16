---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Encapsule la valeur du membre d'énumération de l'énumération spécifiée avec le nom indiqué. Un paramètre indique si la casse doit être ignorée lors de l'interprétation de la chaîne spécifiant le nom du membre d'énumération.
type: docs
weight: 53
url: /fr/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) méthode


Encapsule la valeur du membre d'énumération de l'énumération spécifiée avec le nom indiqué. Un paramètre indique si la casse doit être ignorée lors de l'interprétation de la chaîne spécifiant le nom du membre d'énumération.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Spécifie le type de l'énumération |
| str | const [String](../../string/)\& | Le nom du membre d'énumération dont la valeur doit être encapsulée |
| ignoreCase | **bool** | Indique si la casse doit être ignorée lors de l'interprétation de la chaîne représentant le nom du membre d'énumération |

### Valeur de retour

Un pointeur partagé vers l'objet représentant la valeur encapsulée du membre d'énumération spécifié

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) méthode


Encapsule la valeur du membre d'énumération de l'énumération spécifiée avec le nom indiqué.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Spécifie le type de l'énumération |
| str | const [String](../../string/)\& | Le nom du membre d'énumération dont la valeur doit être encapsulée |

### Valeur de retour

Un pointeur partagé vers l'objet représentant la valeur encapsulée du membre d'énumération spécifié

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [BoxedValueBase](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)