---
title: TryParse()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu single-precision floating-point value.
type: docs
weight: 14
url: /cs/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností (single-precision) typu floating-point.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| result | **float**\& | Reference na proměnnou typu single-precision floating-point, kam se uloží výsledek převodu. |

### Návratová hodnota

True pokud konverze uspěla, jinak – false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností typu floating-point za použití poskytnutých informací o formátování a stylu čísla.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |
| result | **float**\& | Reference na proměnnou typu single-precision floating-point, kam se uloží výsledek převodu. |

### Návratová hodnota

True pokud konverze uspěla, jinak – false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) metoda




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)