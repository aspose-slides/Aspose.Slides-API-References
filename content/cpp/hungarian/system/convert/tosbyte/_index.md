---
title: ToSByte()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a megadott logikai értéket egy ekvivalens 8-bites előjeles egész számmá.
type: docs
weight: 105
url: /hu/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metódus


Átalakítja a megadott logikai értéket egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) metódus


Átalakítja a megadott 8-bites előjel nélküli egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) metódus


Visszaadja a megadott 8-bites előjeles egész számot.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) metódus


Átalakítja a megadott 16-bites előjel nélküli egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) metódus


Átalakítja a megadott 16-bites előjeles egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) metódus


Átalakítja a megadott 32-bites előjel nélküli egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) metódus


Átalakítja a megadott 32-bites előjeles egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) metódus


Átalakítja a megadott 64-bites előjel nélküli egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) metódus


Átalakítja a megadott 64-bites előjeles egész számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) metódus


Átalakítja a megadott lebegőpontos számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) metódus


Átalakítja a megadott dupla pontosságú számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) metódus


Átalakítja a megadott decimális számot egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) metódus


Átalakítja a megadott Unicode karaktert egy ekvivalens 8-bites előjeles egész számmá.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) metódus


Átalakítja a megadott null-karakterláncot a megfelelő 8-bites egész értékké.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Visszatérési érték

Nulla.

## Convert::ToSByte(const char_t *) metódus


Átalakítja a megadott c-karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az átalakítandó c-karakterlánc |

### Visszatérési érték

A megadott c-karakterlánc által képviselt számnak megfelelő 8-bites egész érték

## Convert::ToSByte(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |

### Visszatérési érték

A megadott karakterlánc által képviselt számnak megfelelő 8-bites egész érték

## Convert::ToSByte(const String\&, int) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza a megadott alapban, a megfelelő 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| from_base | int | A szám alapja, amelyet a karakterlánc képvisel |

### Visszatérési érték

A megadott karakterlánc által képviselt számnak megfelelő 8-bites egész érték

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megadott formázási információk használatával előjel nélküli 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A megadott karakterlánc által képviselt számnak megfelelő 8-bites előjel nélküli egész érték

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megadott formázási információk és számstílus használatával a megfelelő 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

Az előjel nélküli 8-bites egész érték, amely megegyezik a megadott karakterlánc által képviselt számmal

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metódus




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozott értéket ekvivalens 8-bites egész értékké.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket tartalmazza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A formátum, amelyet akkor használunk, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

Egy 8-bites egész érték, amely ekvivalens a megadott dobozott értékkel

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