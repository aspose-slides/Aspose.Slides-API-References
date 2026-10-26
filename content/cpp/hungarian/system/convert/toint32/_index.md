---
title: ToInt32()
second_title: Aspose.Slides for C++ API-referencia
description: Átalakítja a megadott logikai értéket egy ekvivalens 32 bites előjeles egész számmá.
type: docs
weight: 157
url: /hu/system/convert/toint32/
---
## Convert::ToInt32(bool) metódus

Átalakítja a megadott logikai értéket egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```
## Convert::ToInt32(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```
## Convert::ToInt32(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```
## Convert::ToInt32(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```
## Convert::ToInt32(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```
## Convert::ToInt32(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```
## Convert::ToInt32(int32_t) metódus

Visszaadja a megadott 32 bites előjeles egész számot.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```
## Convert::ToInt32(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```
## Convert::ToInt32(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(int64_t value)
```
## Convert::ToInt32(float) metódus

Átalakítja a megadott float számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(float value)
```
## Convert::ToInt32(double) metódus

Átalakítja a megadott double számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(double value)
```
## Convert::ToInt32(const Decimal\&) metódus

Átalakítja a megadott decimal számot egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```
## Convert::ToInt32(char_t) metódus

Átalakítja a megadott unicode karaktert egy ekvivalens 32 bites előjeles egész számmá.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```
## Convert::ToInt32(DateTime) metódus

Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static int System::Convert::ToInt32(DateTime value)
```
## Convert::ToInt32(std::nullptr_t) metódus

Átalakítja a megadott null karakterláncot az ekvivalens 32 bites egész értékre.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```


### Visszatérési érték

Nulla.

## Convert::ToInt32(const char_t *) metódus


Átalakítja a megadott c-karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 32 bites egész értékre.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-karakterlánc |

### Visszatérési érték

A 32 bites egész érték, amely megegyezik a megadott c-karakterlánc által képviselt számmal

## Convert::ToInt32(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 32 bites egész értékre.

```cpp
static int System::Convert::ToInt32(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |

### Visszatérési érték

A 32 bites egész érték, amely megegyezik a megadott karakterlánc által képviselt számmal

## Convert::ToInt32(const String\&, int) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza a megadott alapon, az ekvivalens 32 bites egész értékre.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| from_base | int | A karakterlánc által képviselt szám alapszáma |

### Visszatérési érték

A 32 bites egész érték, amely megegyezik a megadott karakterlánc által képviselt számmal

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 32 bites egész értékre a megadott formázási információk segítségével.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

A 32 bites egész érték, amely megegyezik a megadott karakterlánc által képviselt számmal

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) metódus




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 32 bites egész értékre a megadott formázási információk és számformátum stílus használatával.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékeinek bitenkénti kombinációja, amely meghatározza a szám sztring reprezentációjának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

A 32 bites egész érték, amely megegyezik a megadott karakterlánc által képviselt számmal

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metódus




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozott értéket egy ekvivalens 32 bites egész számmá.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az értéket dobozzoló objektumra, amelyet konvertálni kell |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A használni kívánt karakterlánc formátum, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

A 32 bites egész érték, amely ekvivalens a megadott dobozott értékkel

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Decimal](../../decimal/)
* Osztály [DateTime](../../datetime/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Osztály [Object](../../object/)
* Struktúra [Convert](../)
* Struktúra [Enum](../../enum/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)