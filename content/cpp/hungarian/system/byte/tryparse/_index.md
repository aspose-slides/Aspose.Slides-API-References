---
title: TryParse()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjel nélküli egész számmá.
type: docs
weight: 14
url: /hu/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **uint8_t**\& | A hivatkozás egy 8 bites előjel nélküli egész változóhoz, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikerült, egyébként - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjel nélküli egész számmá a megadott formázási információk és számstílus alapján.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy pointer egy olyan objektumra, amely a karakterlánc formátuminformációit tartalmazza. |
| result | **uint8_t**\& | A hivatkozás egy 8 bites előjel nélküli egész változóhoz, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikerült, egyébként - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) metódus

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) metódus

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) metódus

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Byte](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)