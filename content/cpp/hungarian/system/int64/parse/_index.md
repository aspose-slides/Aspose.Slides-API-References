---
title: Parse()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 64-bit előjeles egészre.
type: docs
weight: 1
url: /hu/system/int64/parse/
---
## Int64::Parse(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 64-bit előjeles egészre.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |

### Visszatérési érték

Az a 64-bit előjeles egész, amely egyenlő a megadott karakterlánc által képviselt számmal.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 64-bit előjeles egészre a megadott formázási információk használatával.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza. |

### Visszatérési érték

Az a 64-bit előjeles egész, amely egyenlő a megadott karakterlánc által képviselt számmal.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, az ekvivalens 64-bit előjeles egészre a megadott formázási információk és számformátum használatával.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsoroló értékeinek bitenkénti kombinációja, amely meghatározza a szám karakterlánc reprezentációjának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza. |

### Visszatérési érték

Az a 64-bit előjeles egész, amely egyenlő a megadott karakterlánc által képviselt számmal.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)