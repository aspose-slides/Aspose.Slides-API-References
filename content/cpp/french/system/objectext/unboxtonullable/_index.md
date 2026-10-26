---
title: UnboxToNullable()
second_title: Référence API Aspose.Slides pour C++
description: Déballe l'objet vers un type nullable.
type: docs
weight: 79
url: /fr/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) méthode


Déballe l'objet vers un type nullable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de destination. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) à déballer. |
| safe | **bool** | Si vrai, renvoie nullptr en cas d'échec, sinon lève InvalidCastException. |

### Valeur de retour

Valeur nullable déballee (peut être nulle).

## Voir aussi

* Classe [Nullable](../../nullable/)
* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)