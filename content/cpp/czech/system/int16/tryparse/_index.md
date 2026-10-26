---
title: TryParse()
second_title: Aspose.Slides pro C++ - API reference
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo.
type: docs
weight: 14
url: /cs/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| result | **int16_t**\& | Reference na 16-bitovou podepsanou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

Vrací True, pokud byl převod úspěšný, jinak - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo za použití poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **int16_t**\& | Reference na 16-bitovou podepsanou celočíselnou proměnnou, kam se uloží výsledek převodu. |

### Návratová hodnota

Vrací True, pokud byl převod úspěšný, jinak - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metoda




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Int16](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)