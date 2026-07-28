---
title: ParseExact()
second_title: Aspose.Slides C++ API Referenciája
description: Átalakítja a karakterláncot a megadott formátumok, formátumszolgáltató és stílusok használatával a megfelelő TimeSpan objektummá.
type: docs
weight: 547
url: /hu/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá a megadott formátumok, formátumszolgáltató és stílusok használatával.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) formátum karakterláncok. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató, amely a kultúrára jellemző formázási információkat biztosítja. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Meghatározza az elemeket, amelyek a bemeneti karakterláncban előfordulhatnak. |

### Visszatérési érték

Az időintervallum, amely megfelel a karakterláncnak.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá a megadott formátum, formátumszolgáltató és stílusok használatával.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| format | const [String](../../string/)\& | Standard vagy egyéni formátum karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató, amely a kultúrára jellemző formázási információkat biztosítja. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Meghatározza az elemeket, amelyek a bemeneti karakterláncban előfordulhatnak. |

### Visszatérési érték

Az időintervallum, amely megfelel a karakterláncnak.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## Lásd még

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [TimeSpan](../)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)