---
title: ToDateTime()
second_title: Aspose.Slides C++ API referenciája
description: A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.
type: docs
weight: 248
url: /hu/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt vált ki.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metódus

Visszaadja a megadott dátumot és időt.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metódus

Átalakítja a megadott karakterláncot a(z) [DateTime](../../datetime/) osztály egy példányává.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |

### Visszatérési érték

A(z) [DateTime](../../datetime/) osztály egy példánya, amely a megadott karakterlánc által ábrázolt dátum- és időinformációt tartalmazza.

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot a(z) [DateTime](../../datetime/) osztály egy példányává a megadott formázási információk felhasználásával.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A(z) [DateTime](../../datetime/) osztály egy példánya, amely a megadott karakterlánc által ábrázolt dátum- és időinformációt tartalmazza.

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metódus

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metódus

```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott dobozolt értéket az egyenértékű [DateTime](../../datetime/) értékké.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket becsomagolja |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Az a karakterlánc formátum, amelyet akkor kell használni, ha a becsomagolt érték típusa [String](../../string/) |

### Visszatérési érték

Egy [DateTime](../../datetime/) érték, amely egyenértékű a megadott becsomagolt értékkel.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [DateTime](../../datetime/)
* Osztály [Decimal](../../decimal/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Osztály [Object](../../object/)
* Struktúra [Convert](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)