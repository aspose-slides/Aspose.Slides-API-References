---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 32 bites előjel nélküli egész számmá.
type: docs
weight: 1
url: /hu/system/uint32/parse/
---
## UInt32::Parse(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 32 bites előjel nélküli egész számmá.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |

### Visszatérési érték

A 32 bites előjel nélküli egész szám, amely egyenlő a megadott karakterlánc által ábrázolt számmal.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 32 bites előjel nélküli egész számmá a megadott formázási információk felhasználásával.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy objektumra, amely a karakterlánc formázási információit tartalmazza. |

### Visszatérési érték

A 32 bites előjel nélküli egész szám, amely egyenlő a megadott karakterlánc által ábrázolt számmal.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 32 bites előjel nélküli egész számmá a megadott formázási információk és számstílus felhasználásával.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsoroló bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy objektumra, amely a karakterlánc formázási információit tartalmazza. |

### Visszatérési érték

A 32 bites előjel nélküli egész szám, amely egyenlő a megadott karakterlánc által ábrázolt számmal.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktúra [UInt32](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)