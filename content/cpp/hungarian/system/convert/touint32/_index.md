---
title: ToUInt32()
second_title: Aspose.Slides C++ API hivatkozás
description: Átalakítja a megadott logikai értéket egy ekvivalens 32-bites előjel nélküli egész számmá.
type: docs
weight: 170
url: /hu/system/convert/touint32/
---
## Convert::ToUInt32(bool) metódus

Átalakítja a megadott logikai értéket egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```
## Convert::ToUInt32(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```
## Convert::ToUInt32(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```
## Convert::ToUInt32(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```
## Convert::ToUInt32(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```
## Convert::ToUInt32(uint32_t) metódus

Visszaadja a megadott 32 bites előjel nélküli egész számot.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```
## Convert::ToUInt32(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```
## Convert::ToUInt32(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```
## Convert::ToUInt32(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```
## Convert::ToUInt32(float) metódus

Átalakítja a megadott float számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```
## Convert::ToUInt32(double) metódus

Átalakítja a megadott double számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```
## Convert::ToUInt32(const Decimal\&) metódus

Átalakítja a megadott decimal számot egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```
## Convert::ToUInt32(char_t) metódus

Átalakítja a megadott unicode karaktert egy ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```
## Convert::ToUInt32(DateTime) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```
## Convert::ToUInt32(std::nullptr_t) metódus

Átalakítja a megadott null-karakterláncot az ekvivalens előjel nélküli 32 bites egész értékké.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Visszatérési érték

Nulla.

## Convert::ToUInt32(const char_t *) metódus

Átalakítja a megadott c-stringet, amely számábrázolást tartalmaz, az ekvivalens előjel nélküli 32 bites egész értékké.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-string |

### Visszatérési érték

Az a előjel nélküli 32 bites egész érték, amely megegyezik a megadott c-string által ábrázolt számmal.

## Convert::ToUInt32(const String\&) metódus

Átalakítja a megadott stringet, amely számábrázolást tartalmaz, az ekvivalens előjel nélküli 32 bites egész értékké.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |

### Visszatérési érték

Az a előjel nélküli 32 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToUInt32(const String\&, int) metódus

Átalakítja a megadott stringet, amely a szám ábrázolását tartalmazza a megadott alapon, az ekvivalens előjel nélküli 32 bites egész értékké.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| from_base | int | A szám alapja, amelyet a string ábrázol |

### Visszatérési érték

Az a előjel nélküli 32 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott stringet, amely számábrázolást tartalmaz, az ekvivalens előjel nélküli 32 bites egész értékké a megadott formázási információk felhasználásával.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

Az a előjel nélküli 32 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metódus




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott stringet, amely számábrázolást tartalmaz, az ekvivalens előjel nélküli 32 bites egész értékké a megadott formázási információk és számstílus felhasználásával.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitwise kombinációja, amely meghatározza a számábrázolás engedélyezett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

Az a előjel nélküli 32 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metódus 




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott dobozott értéket az ekvivalens előjel nélküli 32 bites egész értékké.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A használandó karakterlánc formátum, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

Egy előjel nélküli 32 bites egész érték, amely ekvivalens a megadott dobozott értékkel.

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