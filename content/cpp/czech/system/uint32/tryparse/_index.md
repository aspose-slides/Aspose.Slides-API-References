---
title: TryParse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neznačené celé číslo.
type: docs
weight: 14
url: /cs/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method


Převádí zadaný řetězec typu String, který obsahuje textovou reprezentaci čísla, na ekvivalentní 32-bitové neznačené celé číslo.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| result | **uint32_t**\& | Reference na 32-bitovou neznačenou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud převod uspěl, jinak - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method


Převádí zadaný řetězec typu String, který obsahuje textovou reprezentaci čísla, na ekvivalentní 32-bitové neznačené celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **uint32_t**\& | Reference na 32-bitovou neznačenou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

True, pokud převod uspěl, jinak - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)