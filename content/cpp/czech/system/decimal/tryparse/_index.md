---
title: TryParse()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu Decimal.
type: docs
weight: 482
url: /cs/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| result | [Decimal](../)\& | Odkaz na proměnnou [Decimal](../), kde se uloží výsledek převodu |

### Návratová hodnota

True, pokud byl převod úspěšný, jinak - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../) pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |
| result | [Decimal](../)\& | Výstupní argument; obsahuje výsledek převodu |

### Návratová hodnota

True, pokud byl převod úspěšný, jinak - false

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)