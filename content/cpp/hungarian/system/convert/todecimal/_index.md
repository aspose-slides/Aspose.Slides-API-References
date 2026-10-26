---
title: ToDecimal()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott logikai értéket egy ekvivalens decimális számmá.
type: docs
weight: 235
url: /hu/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metódus

Átalakítja a megadott logikai értéket egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metódus

Átalakítja a megadott lebegőpontos számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metódus

Átalakítja a megadott dupla pontosságú lebegőpontos számot egy ekvivalens decimális számmá.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metódus

Visszaadja a megadott decimális számot.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metódus

Az átalakítás nem támogatott. Mindig InvalidCastException-t dob.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metódus

Az átalakítás nem támogatott. Mindig InvalidCastException-t dob.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metódus

Átalakítja a megadott null karakterláncot az ekvivalens [Decimal](../../decimal/) értékre.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Visszatérési érték

Nulla.

## Convert::ToDecimal(const char_t *) metódus

Átalakítja a megadott c-karakterláncot, amely szám sztring reprezentációját tartalmazza, az ekvivalens [Decimal](../../decimal/) értékre.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az átalakítandó c-karakterlánc |

### Visszatérési érték

A [Decimal](../../decimal/) érték, amely megegyezik a megadott c-karakterláncban szereplő szám értékével

## Convert::ToDecimal(const String\&) metódus

Átalakítja a megadott karakterláncot, amely szám sztring reprezentációját tartalmazza, az ekvivalens [Decimal](../../decimal/) értékre.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |

### Visszatérési érték

A [Decimal](../../decimal/) érték, amely megegyezik a megadott karakterláncban szereplő szám értékével

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely szám sztring reprezentációját tartalmazza, az ekvivalens [Decimal](../../decimal/) értékre a megadott formázási információk használatával.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A [Decimal](../../decimal/) érték, amely megegyezik a megadott karakterláncban szereplő szám értékével

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely szám sztring reprezentációját tartalmazza, az ekvivalens [Decimal](../../decimal/) értékre a megadott számstílusok és formázási információk használatával.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám sztring reprezentációjának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátum információkat tartalmazza |

### Visszatérési érték

A [Decimal](../../decimal/) érték, amely megegyezik a megadott karakterláncban szereplő szám értékével

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott dobozott értéket az ekvivalens [Decimal](../../decimal/) értékre.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor használunk, ha a dobozott érték típusa [String](../../string/) |

### Visszatérési érték

Egy [Decimal](../../decimal/) érték, amely ekvivalens a megadott dobozott értékkel

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)