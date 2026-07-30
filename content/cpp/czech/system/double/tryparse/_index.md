---
title: TryParse()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu double s dvojitou přesností.
type: docs
weight: 14
url: /cs/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu double.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převedení. |
| result | **double**\& | Odkaz na proměnnou typu double, kam se uloží výsledek převodu. |

### Návratová hodnota

True pokud převod uspěl, jinak - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu double za použití poskytnutých informací o formátování a stylu čísel.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převedení. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce. |
| result | **double**\& | Odkaz na proměnnou typu double, kam se uloží výsledek převodu. |

### Návratová hodnota

True pokud převod uspěl, jinak - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) metoda




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)