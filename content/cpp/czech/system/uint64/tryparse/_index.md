---
title: TryParse()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové nepodepsané celé číslo.
type: docs
weight: 14
url: /cs/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové nepodepsané celé číslo.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| result | **uint64_t**\& | Reference na 64bitovou nepodepsanou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud převod uspěl, jinak - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové nepodepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |
| result | **uint64_t**\& | Reference na 64bitovou nepodepsanou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud převod uspěl, jinak - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) metoda




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) metoda




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) metoda




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [UInt64](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)