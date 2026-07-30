---
title: Parse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64-bitové neznaménkové celé číslo.
type: docs
weight: 1
url: /cs/system/uint64/parse/
---
## UInt64::Parse(const String\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové neznaménkové celé číslo.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |

### Návratová hodnota

64bitové neznaménkové celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové neznaménkové celé číslo pomocí poskytnutých informací o formátování.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |

### Návratová hodnota

64bitové neznaménkové celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 64bitové neznaménkové celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |

### Návratová hodnota

64bitové neznaménkové celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [UInt64](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)