---
title: TryParse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a karakterláncot a megfelelő TimeSpan objektummá, és visszaadja a konverzió eredményét.
type: docs
weight: 560
url: /hu/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metódus


Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá, és visszaadja az átalakítás eredményét.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| result | [TimeSpan](../)\& | Időintervallum, amely a karakterláncnak megfelelő. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálva lett; egyébként hamis.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metódus


Átalakítja a karakterláncot a megfelelő [TimeSpan](../) objektummá a megadott formázási szolgáltató használatával, és visszaadja az átalakítás eredményét.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | Bemeneti karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formázási szolgáltató, amely kultúrafüggő formázási információkat biztosít. |
| result | [TimeSpan](../)\& | Időintervallum, amely a karakterláncnak megfelelő. |

### Visszatérési érték

Igaz, ha a karakterlánc sikeresen konvertálva lett; egyébként hamis.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metódus




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [TimeSpan](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)