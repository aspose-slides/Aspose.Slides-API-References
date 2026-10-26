---
title: TryParse()
second_title: Aspose.Slides pro C++ API Reference
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nepodepsané celé číslo.
type: docs
weight: 14
url: /cs/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nepodepsané celé číslo.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| result | **uint16_t**\& | Odkaz na proměnnou typu 16-bitové nepodepsané celé číslo, do které se uloží výsledek převodu. |

### Návratová hodnota

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nepodepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |
| result | **uint16_t**\& | Odkaz na proměnnou typu 16-bitové nepodepsané celé číslo, do které se uloží výsledek převodu. |

### Návratová hodnota

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)