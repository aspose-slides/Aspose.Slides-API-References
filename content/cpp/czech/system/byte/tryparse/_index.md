---
title: TryParse()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí zadaný řetězec, který obsahuje textovou reprezentaci čísla, na ekvivalentní 8-bitové nezáporné celé číslo.
type: docs
weight: 14
url: /cs/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) metoda

Převádí zadaný řetězec, který obsahuje textovou reprezentaci čísla, na ekvivalentní 8-bitové nezáporné celé číslo.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| result | **uint8_t**\& | Odkaz na proměnnou typu 8-bitové nezáporné celé číslo, do které se uloží výsledek převodu. |

### Návratová hodnota

True pokud konverze uspěla, jinak - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) metoda

Převádí zadaný řetězec, který obsahuje textovou reprezentaci čísla, na ekvivalentní 8-bitové nezáporné celé číslo pomocí poskytnutých informací o formátování a stylu čísel.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **uint8_t**\& | Odkaz na proměnnou typu 8-bitové nezáporné celé číslo, do které se uloží výsledek převodu. |

### Návratová hodnota

True pokud konverze uspěla, jinak - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) metoda




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) metoda




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) metoda




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* třída [String](../../string/)
* třída [Byte](../)
* třída [IFormatProvider](../../iformatprovider/)
* třída [CultureInfo](../../../system.globalization/cultureinfo/)
* třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)