---
title: ToUInt64()
second_title: Aspose.Slides for C++ API-referencia
description: Átalakítja a megadott logikai értéket egy megfelelő 64 bites előjel nélküli egész számmá.
type: docs
weight: 196
url: /hu/system/convert/touint64/
---
## Convert::ToUInt64(bool) metódus

Átalakítja a megadott logikai értéket egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metódus

Visszaadja a megadott 64 bites előjel nélküli egész számot.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metódus

Átalakítja a megadott float számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metódus

Átalakítja a megadott double számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metódus

Átalakítja a megadott decimális számot egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metódus

Átalakítja a megadott unicode karaktert egy megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metódus

Átalakítja a megadott null-karakterláncot a megfelelő előjel nélküli 64 bites egész szám értékévé.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```

### Visszatérési érték

Nulla.

## Convert::ToUInt64(const char_t *) metódus

Átalakítja a megadott c-karakterláncot, amely egy szám szöveges reprezentációját tartalmazza, a megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-karakterlánc |

### Visszatérési érték

Az előjel nélküli 64 bites egész szám értéke, amely megegyezik a megadott c-karakterláncban szereplő szám értékével.

## Convert::ToUInt64(const String\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges reprezentációját tartalmazza, a megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |

### Visszatérési érték

Az előjel nélküli 64 bites egész szám értéke, amely megegyezik a megadott karakterláncban szereplő szám értékével.

## Convert::ToUInt64(const String\&, int) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges reprezentációját tartalmazza a megadott számrendszerben, a megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| from_base | int | A szám bázisa, amelyet a karakterlánc reprezentál |

### Visszatérési érték

Az előjel nélküli 64 bites egész szám értéke, amely megegyezik a megadott karakterláncban szereplő szám értékével.

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges reprezentációját tartalmazza, a megadott formázási információk felhasználásával a megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

Az előjel nélküli 64 bites egész szám értéke, amely megegyezik a megadott karakterláncban szereplő szám értékével.

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges reprezentációját tartalmazza, a megadott formázási információk és számstílus felhasználásával a megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges reprezentációjának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza |

### Visszatérési érték

Az előjel nélküli 64 bites egész szám értéke, amely megegyezik a megadott karakterláncban szereplő szám értékével.

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metódus

```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott dobozolt értéket egy megfelelő előjel nélküli 64 bites egész szám értékké.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A használandó karakterlánc formátum, ha a dobozolt érték típusa [String](../../string/) |

### Visszatérési érték

Egy előjel nélküli 64 bites egész szám érték, amely megegyezik a megadott dobozolt értékkel.

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