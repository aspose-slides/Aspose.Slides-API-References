---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám sztringábrázolását tartalmazza, egyenlő 8 bites előjel nélküli egész számra.
type: docs
weight: 1
url: /hu/system/byte/parse/
---
## Byte::Parse(const String\&) metódus


Az adott karakterláncot, amely egy szám sztringábrázolását tartalmazza, egyenlő 8 bites előjel nélküli egész számra konvertálja.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |

### Visszatérési érték

Az adott karakterlánc által ábrázolt számot egyenlő 8 bites előjel nélküli egész számként adja vissza.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Az adott karakterláncot, amely egy szám sztringábrázolását tartalmazza, a megadott formázási információk használatával egyenlő 8 bites előjel nélküli egész számra konvertálja.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formázási információkat tartalmaz. |

### Visszatérési érték

Az adott karakterlánc által ábrázolt számot egyenlő 8 bites előjel nélküli egész számként adja vissza.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Az adott karakterláncot, amely egy szám sztringábrázolását tartalmazza, a megadott formázási információk és a számstílus használatával egyenlő 8 bites előjel nélküli egész számra konvertálja.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám sztringábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formázási információkat tartalmaz. |

### Visszatérési érték

Az adott karakterlánc által ábrázolt számot egyenlő 8 bites előjel nélküli egész számként adja vissza.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Byte](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)