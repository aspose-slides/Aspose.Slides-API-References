---
title: ToSingle()
second_title: Aspose.Slides for C++ API referenciája
description: Átalakítja a megadott logikai értéket egy egypontos lebegőpontos számmá.
type: docs
weight: 209
url: /hu/system/convert/tosingle/
---
## Convert::ToSingle(bool) metódus

Átalakítja a megadott logikai értéket egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```
## Convert::ToSingle(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```
## Convert::ToSingle(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```
## Convert::ToSingle(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```
## Convert::ToSingle(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```
## Convert::ToSingle(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```
## Convert::ToSingle(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```
## Convert::ToSingle(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```
## Convert::ToSingle(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```
## Convert::ToSingle(float) metódus

Visszaadja a megadott float értéket.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```
## Convert::ToSingle(double) metódus

Átalakítja a megadott dupla pontosságú számot egy egypontos lebegőpontos számmá.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```
## Convert::ToSingle(const Decimal\&) metódus

Átalakítja a megadott decimális számot egy egypontos lebegőpontos számmá.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```
## Convert::ToSingle(char_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static float System::Convert::ToSingle(char_t value)
```
## Convert::ToSingle(DateTime) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static float System::Convert::ToSingle(DateTime value)
```
## Convert::ToSingle(std::nullptr_t) metódus

Átalakítja a megadott null-karakterláncot egy egypontos lebegőpontos értékké.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```


### Visszatérési érték

Nulla.

## Convert::ToSingle(const char_t *) metódus


Átalakítja a megadott c-stringet, amely egy szám szöveges ábrázolását tartalmazza, az egyenértékű egypontos lebegőpontos értékké.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-karakterlánc |

### Visszatérési érték

Az egypontos lebegőpontos érték, amely megegyezik a megadott c-karakterlánc által ábrázolt számmal

## Convert::ToSingle(const String\&) metódus


Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, az egyenértékű egypontos lebegőpontos értékké.

```cpp
static float System::Convert::ToSingle(const String &value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |

### Visszatérési érték

Az egypontos lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, az egyenértékű egypontos lebegőpontos értékké a megadott formázási információk felhasználásával.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy pointer egy olyan objektumra, amely a karakterlánc formátuminformációkat tartalmaz |

### Visszatérési érték

Az egypontos lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metódus




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, az egyenértékű egypontos lebegőpontos értékké a megadott formázási információk és számstílus felhasználásával.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám karakterlánc ábrázolásának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy pointer egy olyan objektumra, amely a karakterlánc formátuminformációkat tartalmaz |

### Visszatérési érték

Az egypontos lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozott értéket egypontos lebegőpontos értékké.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely becsomagolja a konvertálandó értéket |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor használnak, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

Egy egypontos lebegőpontos érték, amely megegyezik a megadott dobozott értékkel

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)