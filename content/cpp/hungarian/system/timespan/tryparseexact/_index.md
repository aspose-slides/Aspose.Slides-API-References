---
title: TryParseExact()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a karakterláncot a megadott formátumok és formátum-szolgáltató használatával egyenértékű TimeSpan objektummá, és visszaadja a konverzió eredményét.
type: docs
weight: 573
url: /hu/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metódus


Átalakítja a karakterláncot a megadott formátumok és formátum-szolgáltató használatával egyenértékű [TimeSpan](../) objektummá, és visszaadja a konverzió eredményét.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) formátumkarakterláncok. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum-szolgáltató, amely kultúrafüggő formázási információkat biztosít. |
| result | [TimeSpan](../)\& | Időtartam, amely megfelel a karakterláncnak. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálódott; egyébként hamis.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus


Átalakítja a karakterláncot a megadott formátum, formátum-szolgáltató és stílusok használatával egyenértékű [TimeSpan](../) objektummá, és visszaadja a konverzió eredményét.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| format | const [String](../../string/)\& | Standard vagy egyéni formátumkarakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum-szolgáltató, amely kultúrafüggő formázási információkat biztosít. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Meghatározza azokat az elemeket, amelyek a bemeneti karakterláncban előfordulhatnak. |
| result | [TimeSpan](../)\& | Időtartam, amely megfelel a karakterláncnak. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálódott; egyébként hamis.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus


Átalakítja a karakterláncot a megadott formátumok, formátum-szolgáltató és stílusok használatával egyenértékű [TimeSpan](../) objektummá, és visszaadja a konverzió eredményét.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) formátumkarakterláncok. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum-szolgáltató, amely kultúrafüggő formázási információkat biztosít. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Meghatározza azokat az elemeket, amelyek a bemeneti karakterláncban előfordulhatnak. |
| result | [TimeSpan](../)\& | Időtartam, amely megfelel a karakterláncnak. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálódott; egyébként hamis.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metódus


Átalakítja a karakterláncot a megadott formátum és formátum-szolgáltató használatával egyenértékű [TimeSpan](../) objektummá, és visszaadja a konverzió eredményét.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| format | const [String](../../string/)\& | Standard vagy egyéni formátumkarakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum-szolgáltató, amely kultúrafüggő formázási információkat biztosít. |
| result | [TimeSpan](../)\& | Időtartam, amely megfelel a karakterláncnak. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálódott; egyébként hamis.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Lásd még

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [TimeSpan](../)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)