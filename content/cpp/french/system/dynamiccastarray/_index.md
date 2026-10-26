---
title: DynamicCastArray()
second_title: Référence API Aspose.Slides pour C++
description: Effectue le cast des éléments du tableau spécifié vers un type différent.
type: docs
weight: 2952
url: /fr/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) fonction

Effectue le cast des éléments du tableau spécifié vers un type différent.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| To | Le type vers lequel les éléments du tableau spécifié sont castés |
| From | Le type des éléments du tableau dont les éléments doivent être castés |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Pointeur partagé vers le tableau contenant les éléments à caster |

### Valeur de retour

Un pointeur vers un nouveau tableau contenant des éléments de type **To** équivalents aux éléments de **from**

Obsolète
:   Ajouté pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Classe [Array](../array/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)