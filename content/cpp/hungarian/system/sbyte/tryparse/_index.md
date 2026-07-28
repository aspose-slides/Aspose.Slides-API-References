---
title: TryParse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá.
type: docs
weight: 14
url: /hu/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **int8_t**\& | Az a 8 bites előjeles egész változó referenciája, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

Igaz, ha a konverzió sikeres, egyébként - hamis.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, az ekvivalens 8 bites előjeles egész számmá a megadott formázási információk és számstílus felhasználásával.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt típusú értékek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató mutató, amely a karakterlánc formátuminformációit tartalmazza. |
| result | **int8_t**\& | Az a 8 bites előjeles egész változó referenciája, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

Igaz, ha a konverzió sikeres, egyébként - hamis.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) metódus




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) metódus




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) metódus




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktúra [SByte](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)