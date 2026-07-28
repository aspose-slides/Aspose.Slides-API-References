---
title: Parse()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakítja a karakterláncot a megfelelő TimeSpan objektummá.
type: docs
weight: 534
url: /hu/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) metódus

Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |

### Visszatérési érték

Időintervallum, amely a karakterláncnak megfelelő.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá a megadott formázó szolgáltató használatával.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formázó szolgáltató, amely kultúraspecifikus formázási információkat biztosít. |

### Visszatérési érték

Időintervallum, amely a karakterláncnak megfelelő.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metódus




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) metódus




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [TimeSpan](../)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)