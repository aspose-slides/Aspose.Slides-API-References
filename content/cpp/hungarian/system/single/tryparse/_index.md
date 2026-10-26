---
title: TryParse()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő egyszeres pontosságú lebegőpontos értékké.
type: docs
weight: 14
url: /hu/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) metódus


A megadott karakterláncot, mely egy szám szöveges ábrázolását tartalmazza, a megfelelő egyszeres pontosságú lebegőpontos értékké alakítja.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **float**\& | Az egyszeres pontosságú lebegőpontos változó referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) metódus


A megadott karakterláncot, mely egy szám szöveges ábrázolását tartalmazza, a megadott formázási információ és számstílus felhasználásával a megfelelő egyszeres pontosságú lebegőpontos értékké alakítja.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formázási információit tartalmazza. |
| result | **float**\& | Az egyszeres pontosságú lebegőpontos változó referencia, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) metódus




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) metódus




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) metódus




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)