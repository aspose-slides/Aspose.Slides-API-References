---
title: Parse()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí řetězec na ekvivalentní objekt TimeSpan.
type: docs
weight: 534
url: /cs/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) metoda

Převádí řetězec na ekvivalentní objekt [TimeSpan](../).

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Vstupní řetězec. |

### Návratová hodnota

Časový interval odpovídající řetězci.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí řetězec na ekvivalentní objekt [TimeSpan](../) pomocí zadaného poskytovatele formátu.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Vstupní řetězec. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu, který poskytuje informace o formátování specifické pro kulturu. |

### Návratová hodnota

Časový interval odpovídající řetězci.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metoda

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) metoda

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [TimeSpan](../)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)