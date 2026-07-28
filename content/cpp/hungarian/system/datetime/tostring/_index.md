---
title: ToString()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a dátum és idő érték karakterlánc ábrázolását, amelyet az aktuális objektum képvisel, a jelenlegi kultúra által meghatározott formázási konvenciók használatával.
type: docs
weight: 482
url: /hu/system/datetime/tostring/
---
## DateTime::ToString() const metódus

Visszaadja a dátum és idő érték karakterlánc ábrázolását, amelyet az aktuális objektum képvisel, a jelenlegi kultúra által meghatározott formázási konvenciók használatával.

```cpp
String System::DateTime::ToString() const
```

### Visszatérési érték

A jelenlegi objektum által képviselt érték karakterlánc ábrázolása

## DateTime::ToString(const String\&) const metódus

Visszaadja a dátum és idő érték karakterlánc ábrázolását, amelyet az aktuális objektum képvisel, a megadott formátum és a jelenlegi kultúra által meghatározott formázási konvenciók használatával.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátum karakterlánc |

### Visszatérési érték

A jelenlegi objektum által képviselt érték karakterlánc ábrázolása, amely a **format** által meghatározott formátum és a jelenlegi kultúra szerint van formázva.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metódus

Visszaadja a dátum és idő érték karakterlánc ábrázolását, amelyet az aktuális objektum képvisel, a megadott formátuminformációk használatával.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátuminformációt képviselő objektum |

### Visszatérési érték

A jelenlegi objektum által képviselt érték karakterlánc ábrázolása, amely a **formatProvider** által biztosított formátuminformációk szerint van formázva.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metódus




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metódus




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metódus




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metódus

Visszaadja a dátum és idő érték karakterlánc ábrázolását, amelyet az aktuális objektum képvisel, a megadott formátuminformációk használatával.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátum karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátuminformációt képviselő objektum |

### Visszatérési érték

A jelenlegi objektum által képviselt érték karakterlánc ábrázolása, amely a **provider** által biztosított formátuminformáció és a **format** formátum karakterlánc szerint van formázva.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metódus




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metódus




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metódus




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [DateTime](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)