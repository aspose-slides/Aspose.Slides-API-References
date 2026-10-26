---
title: ToInt64()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a megadott logikai értéket egy ekvivalens 64 bites előjeles egész számmá.
type: docs
weight: 183
url: /hu/system/convert/toint64/
---
## Convert::ToInt64(bool) metódus


Átalakítja a megadott logikai értéket egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metódus


Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metódus


Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metódus


Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metódus


Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metódus


Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metódus


Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metódus


Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metódus


Visszaadja a megadott 64 bites előjeles egész számot.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metódus


Átalakítja a megadott float számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metódus


Átalakítja a megadott double számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metódus


Átalakítja a megadott decimális számot egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metódus


Átalakítja a megadott Unicode karaktert egy ekvivalens 64 bites előjeles egész számmá.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metódus


Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metódus


Átalakítja a megadott null-karakterláncot az ekvivalens 64 bites egész értékké.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Visszatérési érték

Nulla.

## Convert::ToInt64(const char_t *) metódus


Átalakítja a megadott c-karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 64 bites egész értékké.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-karakterlánc |

### Visszatérési érték

A 64 bites egész érték, amely megegyezik a megadott c-karakterlánc által reprezentált számmal

## Convert::ToInt64(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 64 bites egész értékké.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |

### Visszatérési érték

A 64 bites egész érték, amely megegyezik a megadott karakterlánc által reprezentált számmal

## Convert::ToInt64(const String\&, int) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 64 bites egész értékké a megadott számrendszerben.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| from_base | int | A szám alapja, amelyet a karakterlánc reprezentál |

### Visszatérési érték

A 64 bites egész érték, amely megegyezik a megadott karakterlánc által reprezentált számmal

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 64 bites egész értékké a megadott formázási információk és a formátum szolgáltató használatával.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A 64 bites egész érték, amely megegyezik a megadott karakterlánc által reprezentált számmal

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 64 bites egész értékké a megadott formázási információk és számstílus használatával.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsoroló típus értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A 64 bites egész érték, amely megegyezik a megadott karakterlánc által reprezentált számmal

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metódus




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozott értéket egy ekvivalens 64 bites egész számmá.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A formátum, amelyet akkor kell használni, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

Egy 64 bites egész érték, amely ekvivalens a megadott dobozott értékkel

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)