---
title: TryParse()
second_title: Aspose.Slides pro C++ API Reference
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové celé číslo se znaménkem.
type: docs
weight: 14
url: /cs/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové celé číslo se znaménkem.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| result | **int32_t**\& | Reference na 32-bitovou proměnnou typu signed integer, kam je umístěn výsledek převodu. |

### Návratová hodnota

True pokud se převod podařil, jinak - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové celé číslo se znaménkem pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **int32_t**\& | Reference na 32-bitovou proměnnou typu signed integer, kam je umístěn výsledek převodu. |

### Návratová hodnota

True pokud se převod podařil, jinak - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) metoda




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) metoda




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) metoda




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Int32](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)