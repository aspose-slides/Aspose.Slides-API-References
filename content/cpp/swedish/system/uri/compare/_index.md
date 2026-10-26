---
title: Compare()
second_title: Aspose.Slides för C++ API-referens
description: Jämför de angivna Uri-objekten med de angivna jämförelsereglerna.
type: docs
weight: 521
url: /sv/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metod

Jämför de angivna [Uri](../)-objekten med de angivna jämförelsereglerna.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Den första jämförelseoperand |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Den andra jämförelseoperand |
| partsToCompare | [UriComponents](../../uricomponents/) | Anger delarna av **uri1** och **uri2** som ska jämföras |
| compareFormat | [UriFormat](../../uriformat/) | Anger teckenavkodningen som används när URI-komponenter jämförs |
| comparisonType | [StringComparison](../../stringcomparison/) | Ett av StringComparison-värdena |

### Returvärde

Ett negativt värde om **uri1** är mindre än **uri2**; 0 om uri1 och uri2 är lika; ett positivt värde om **uri1** är större än **uri2**

## Se även

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)