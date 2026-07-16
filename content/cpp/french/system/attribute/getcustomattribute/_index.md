---
title: GetCustomAttribute()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un attribut personnalisé d'un type spécifié appliqué au type spécifié.
type: docs
weight: 1
url: /fr/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) method

Renvoie un attribut personnalisé d'un type spécifié appliqué au type spécifié.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Type d'attribut dont il est récupéré |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Type de l'attribut à récupérer |

### Valeur de retour

Un attribut récupéré ou null si le type spécifié ne possède pas d'attribut du type spécifié.

## Voir aussi

* Typedef [ptr](../../object/ptr/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [Attribute](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)