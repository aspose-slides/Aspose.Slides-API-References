---
title: TryParse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám sztring reprezentációját tartalmazza, a megfelelő dupla pontosságú lebegőpontos értékké.
type: docs
weight: 14
url: /hu/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) metódus

Átalakítja a megadott karakterláncot, amely szám sztring reprezentációját tartalmazza, a megfelelő dupla pontosságú lebegőpontos értékké.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **double**\& | A dupla pontosságú lebegőpontos változóra mutató referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) metódus

Átalakítja a megadott karakterláncot, amely szám sztring reprezentációját tartalmazza, a megfelelő dupla pontosságú lebegőpontos értékké a megadott formázási információk és számstílus használatával.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékeinek bitenkénti kombinációja, amely meghatározza a szám sztring reprezentációjának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formátuminformációit tartalmazza. |
| result | **double**\& | A dupla pontosságú lebegőpontos változóra mutató referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) metódus




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) metódus




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) metódus




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Lásd még

* Enumeráció [NumberStyles](../../../system.globalization/numberstyles/)
* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktúra [Double](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)