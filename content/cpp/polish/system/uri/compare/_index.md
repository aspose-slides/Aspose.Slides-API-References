---
title: Compare()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Porównuje określone obiekty Uri przy użyciu określonych reguł porównania.
type: docs
weight: 521
url: /pl/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metoda


Porównuje określone [Uri](../) obiekty przy użyciu określonych reguł porównania.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Pierwszy porównywany element |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Drugi porównywany element |
| partsToCompare | [UriComponents](../../uricomponents/) | Określa części **uri1** i **uri2**, które mają być porównane |
| compareFormat | [UriFormat](../../uriformat/) | Określa sposób escapowania znaków używany podczas porównywania **składników URI** |
| comparisonType | [StringComparison](../../stringcomparison/) | Jedna z wartości StringComparison |

### Wartość zwracana

Wartość ujemna, jeśli **uri1** jest mniejsze niż **uri2**; 0, jeśli uri1 i uri2 są równe; wartość dodatnia, jeśli **uri1** jest większe niż **uri2**

## Zobacz także

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Uri](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)