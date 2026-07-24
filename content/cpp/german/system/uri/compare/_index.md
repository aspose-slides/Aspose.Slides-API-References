---
title: Compare()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht die angegebenen Uri-Objekte mithilfe der angegebenen Vergleichsregeln.
type: docs
weight: 521
url: /de/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) Methode

Vergleicht die angegebenen [Uri](../)-Objekte mithilfe der angegebenen Vergleichsregeln.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Der erste Vergleichswert |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Der zweite Vergleichswert |
| partsToCompare | [UriComponents](../../uricomponents/) | Gibt die Teile von **uri1** und **uri2** an, die verglichen werden sollen |
| compareFormat | [UriFormat](../../uriformat/) | Gibt die Zeichenescapierung an, die beim Vergleich von URI-Komponenten verwendet wird |
| comparisonType | [StringComparison](../../stringcomparison/) | Einer der StringComparison-Werte |

### Rückgabewert

Ein negativer Wert, wenn **uri1** kleiner als **uri2** ist; 0, wenn uri1 und uri2 gleich sind; ein positiver Wert, wenn **uri1** größer als **uri2** ist

## Siehe auch

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Uri](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)