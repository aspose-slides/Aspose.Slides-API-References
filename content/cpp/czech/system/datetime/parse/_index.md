---
title: Parse()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt DateTime.
type: docs
weight: 859
url: /cs/system/datetime/parse/
---
## DateTime::Parse(const String\&) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../).

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, která se má převést. |

### Vrácená hodnota

Nová instance třídy [DateTime](../), která představuje hodnotu data a času ekvivalentní té, která je reprezentována zadaným řetězcem.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Převádí zadanou řetězcovou reprezentaci hodnoty data a času na ekvivalentní objekt [DateTime](../) pomocí informací o formátu specifických pro kulturu.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězcová reprezentace hodnoty data a času, která se má převést. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt [IFormatProvider](../../iformatprovider/), který poskytuje informace o formátu specifické pro kulturu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitová kombinace hodnot výčtu, která poskytuje další informace o **s**, o stylech, které mohou být v **s** přítomny, nebo o konverzi ze **s** na objekt [DateTime](../). |

### Vrácená hodnota

Nová instance třídy [DateTime](../), která představuje hodnotu data a času ekvivalentní té, která je reprezentována zadaným řetězcem.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Viz také

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)