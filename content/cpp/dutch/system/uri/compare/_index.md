---
title: Compare()
second_title: Aspose.Slides voor C++ API Referentie
description: Vergelijkt de opgegeven Uri-objecten met de opgegeven vergelijkingsregels.
type: docs
weight: 521
url: /nl/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) methode


Vergelijkt de opgegeven [Uri](../) objecten met de opgegeven vergelijkingsregels.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De eerste vergelijkende |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | De tweede vergelijkende |
| partsToCompare | [UriComponents](../../uricomponents/) | Specificeert de delen van **uri1** en **uri2** om te vergelijken |
| compareFormat | [UriFormat](../../uriformat/) | Specificeert de gebruikte tekenontsnapping wanneer componenten van URI's worden vergeleken |
| comparisonType | [StringComparison](../../stringcomparison/) | Een van de StringComparison-waarden |

### Retourwaarde

Een negatieve waarde wanneer **uri1** kleiner is dan **uri2**; 0 wanneer uri1 en uri2 gelijk zijn; een positieve waarde wanneer **uri1** groter is dan **uri2**

## Zie ook

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Uri](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)