---
title: GetCustomAttributes()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un tableau contenant des objets qui représentent tous les attributs personnalisés appliqués au type représenté par l'objet actuel.
type: docs
weight: 66
url: /fr/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const méthode

Renvoie un tableau contenant des objets qui représentent tous les attributs personnalisés appliqués au type représenté par l'objet actuel.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Type d'attribut à rechercher. |
| inherit | **bool** | Indique s'il faut également vérifier les attributs hérités. |

## MemberInfo::GetCustomAttributes(bool) const méthode

Renvoie un tableau contenant des objets qui représentent tous les attributs personnalisés appliqués au type représenté par l'objet actuel.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inherit | **bool** | Indique s'il faut également vérifier les attributs hérités. |

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)