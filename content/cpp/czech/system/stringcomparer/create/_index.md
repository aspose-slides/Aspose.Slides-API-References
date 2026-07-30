---
title: Create()
second_title: Aspose.Slides pro C++ – API reference
description: Vytvoří srovnávač specifický pro kulturu.
type: docs
weight: 79
url: /cs/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) metoda

Vytvoří srovnávač specifický pro kulturu.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura, pro kterou se vytváří srovnávač. |
| ignoreCase | **bool** | Určuje, zda má srovnávač ignorovat velikost písmen. |

### Return Value

Ukazatel na nově vytvořený objekt srovnávače.

## Viz také

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [StringComparer](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)