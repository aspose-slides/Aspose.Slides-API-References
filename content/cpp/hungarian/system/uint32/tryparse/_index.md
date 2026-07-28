---
title: TryParse()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 32-bit előjel nélküli egész számra.
type: docs
weight: 14
url: /hu/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 32-bit előjel nélküli egész számra.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **uint32_t**\& | A hivatkozás egy 32-bit előjel nélküli egész változóra, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 32-bit előjel nélküli egész számra a megadott formázási információk és számstílus használatával.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enumeráció értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató mutató, amely a karakterlánc formátuminformációit tartalmazza. |
| result | **uint32_t**\& | A hivatkozás egy 32-bit előjel nélküli egész változóra, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) metódus

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) metódus

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) metódus

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)