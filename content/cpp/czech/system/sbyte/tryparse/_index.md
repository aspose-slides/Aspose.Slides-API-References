---
title: TryParse()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitové podepsané celé číslo.
type: docs
weight: 14
url: /cs/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitové podepsané celé číslo.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převedení. |
| result | **int8_t**\& | Odkaz na 8-bitovou podepsanou celočíselnou proměnnou, do které se uloží výsledek převodu. |

### Návratová hodnota

True, pokud byl převod úspěšný, jinak - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8-bitové podepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převedení. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **int8_t**\& | Odkaz na 8-bitovou podepsanou celočíselnou proměnnou, do které se uloží výsledek převodu. |

### Návratová hodnota

True, pokud byl převod úspěšný, jinak - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) metoda




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [SByte](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)