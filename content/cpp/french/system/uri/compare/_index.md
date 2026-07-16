---
title: Compare()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les objets Uri spécifiés en utilisant les règles de comparaison spécifiées.
type: docs
weight: 521
url: /fr/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) méthode

Compare les objets [Uri](../) spécifiés en utilisant les règles de comparaison spécifiées.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The first comparand |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The second comparand |
| partsToCompare | [UriComponents](../../uricomponents/) | Specifies the parts of **uri1** and **uri2** to compare |
| compareFormat | [UriFormat](../../uriformat/) | Specifies the character escaping used when components of URIs are compared |
| comparisonType | [StringComparison](../../stringcomparison/) | One of the StringComparison values |

### Valeur de retour

Une valeur négative si **uri1** est inférieur à **uri2** ; 0 si uri1 et uri2 sont égaux ; une valeur positive si **uri1** est supérieur à **uri2**

## Voir aussi

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)