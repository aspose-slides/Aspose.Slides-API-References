---
title: Compare()
second_title: Aspose.Slides C++ API referencia
description: Összehasonlítja a megadott Uri objektumokat a megadott összehasonlítási szabályok használatával.
type: docs
weight: 521
url: /hu/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metódus

Összehasonlítja a megadott [Uri](../) objektumokat a megadott összehasonlítási szabályok használatával.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az első összehasonlítandó |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | A második összehasonlítandó |
| partsToCompare | [UriComponents](../../uricomponents/) | Megadja a **uri1** és **uri2** összehasonlítandó részeit |
| compareFormat | [UriFormat](../../uriformat/) | Megadja a karakterek escape-elését, amelyet az URI összetevők összehasonlításakor használnak |
| comparisonType | [StringComparison](../../stringcomparison/) | A StringComparison értékek egyike |

### Visszatérési érték

Negatív érték, ha **uri1** kisebb, mint **uri2**; 0, ha uri1 és uri2 egyenlő; pozitív érték, ha **uri1** nagyobb, mint **uri2**

## Lásd még

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)