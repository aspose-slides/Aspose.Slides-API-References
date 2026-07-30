---
title: TryParse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitové celé číslo se znaménkem.
type: docs
weight: 14
url: /cs/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) method


Převede uvedený řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| result | **int64_t**\& | Reference na 64-bitovou proměnnou typu signed integer, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud se převod podařil, jinak - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Převede uvedený řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitové celé číslo se znaménkem pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **int64_t**\& | Reference na 64-bitovou proměnnou typu signed integer, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud se převod podařil, jinak - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Int64](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)