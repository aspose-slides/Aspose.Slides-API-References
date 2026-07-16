---
title: GetCompareInfo()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le CompareInfo associé à la culture spécifiée et utilise les méthodes de comparaison de chaînes dans l'assembly spécifié.
type: docs
weight: 183
url: /fr/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) méthode

Obtient [CompareInfo](../) associé à la culture spécifiée et utilisant les méthodes de comparaison de chaînes dans l'assembly spécifié.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| culture | int | Identifiant de culture (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | assembly qui contient les méthodes de comparaison de chaînes. |

### Valeur de retour

[CompareInfo](../) objet.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) méthode

Obtient [CompareInfo](../) associé à la culture spécifiée et utilisant les méthodes de comparaison de chaînes dans l'assembly spécifié.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nom de la culture. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | assembly qui contient les méthodes de comparaison de chaînes. |

### Valeur de retour

[CompareInfo](../) objet.

## CompareInfo::GetCompareInfo(int) méthode

Obtient [CompareInfo](../) associé à la culture spécifiée.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| culture | int | Identifiant de culture (LCID). |

### Valeur de retour

[CompareInfo](../) objet.

## CompareInfo::GetCompareInfo(const String\&) méthode

Obtient [CompareInfo](../) associé à la culture spécifiée.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nom de la culture. |

### Valeur de retour

[CompareInfo](../) objet.

## Voir aussi

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Assembly](../../../system.reflection/assembly/)
* Classe [CompareInfo](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Globalization](../../)
* Bibliothèque [Aspose.Slides](../../../)