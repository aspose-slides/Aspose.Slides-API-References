---
title: Compare()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Porovnává zadané objekty Uri pomocí určených pravidel porovnání.
type: docs
weight: 521
url: /cs/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metoda

Porovnává specifikované [Uri](../) objekty pomocí specifikovaných pravidel porovnání.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | První porovnávaný |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Druhý porovnávaný |
| partsToCompare | [UriComponents](../../uricomponents/) | Určuje části **uri1** a **uri2**, které se mají porovnat |
| compareFormat | [UriFormat](../../uriformat/) | Určuje únik znaků používaný při porovnávání komponent URI |
| comparisonType | [StringComparison](../../stringcomparison/) | Jedna z hodnot enumerace StringComparison |

### Návratová hodnota

Negativní hodnota, pokud je **uri1** menší než **uri2**; 0, pokud jsou uri1 a uri2 rovny; pozitivní hodnota, pokud je **uri1** větší než **uri2**

## Viz také

* Výčet [UriComponents](../../uricomponents/)
* Výčet [UriFormat](../../uriformat/)
* Výčet [StringComparison](../../stringcomparison/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [Uri](../)
* Obor názvů [System](../../)
* Knihovna [Aspose.Slides](../../../)