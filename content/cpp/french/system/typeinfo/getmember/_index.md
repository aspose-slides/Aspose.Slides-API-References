---
title: GetMember()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la liste des membres portant le nom spécifié.
type: docs
weight: 495
url: /fr/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const méthode

Renvoie la liste des membres ayant le nom spécifié.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | Nom du membre à récupérer. |

### Valeur de retour

[Array](../../array/) de descripteurs de membres (vide si aucun membre n'est trouvé).

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [MemberInfo](../../../system.reflection/memberinfo/)
* Classe [String](../../string/)
* Classe [TypeInfo](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)