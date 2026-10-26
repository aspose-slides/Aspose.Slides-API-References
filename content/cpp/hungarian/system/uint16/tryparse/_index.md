---
title: TryParse()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites előjel nélküli egész számmá.
type: docs
weight: 14
url: /hu/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites előjel nélküli egész számmá.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **uint16_t**\& | A 16 bites előjel nélküli egész változóra mutató referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens 16 bites előjel nélküli egész számmá a megadott formázási információk és számformátum használatával.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formázási információkat tartalmazza. |
| result | **uint16_t**\& | A 16 bites előjel nélküli egész változóra mutató referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) metódus

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) metódus

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) metódus

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)