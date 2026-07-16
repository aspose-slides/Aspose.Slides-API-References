---
title: GetCustomAttributes()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un tableau contenant des objets qui représentent tous les attributs personnalisés appliqués au type.
type: docs
weight: 586
url: /fr/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const méthode

Renvoie un tableau contenant des objets qui représentent tous les attributs personnalisés appliqués au type.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const méthode

Renvoie un tableau contenant des objets qui représentent des attributs spécifiques appliqués au type.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Type de l'attribut à rechercher. |
| inherit | **bool** | Indique s'il faut également rechercher les attributs hérités. |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [SmartPtr](../../smartptr/)
* Classe [TypeInfo](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)