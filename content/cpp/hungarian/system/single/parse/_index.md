---
title: Parse()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens egypontos lebegőpontos értékre.
type: docs
weight: 1
url: /hu/system/single/parse/
---
## Single::Parse(const String\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens egypontos lebegőpontos értékre.

```cpp
static float System::Single::Parse(const String &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |

### Visszatérési érték

Az egyetlen pontosságú lebegőpontos érték, amely megegyezik a megadott karakterlánc által ábrázolt számmal.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens egypontos lebegőpontos értékre a megadott formázási információk felhasználásával.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációkat tartalmazza. |

### Visszatérési érték

Az egyetlen pontosságú lebegőpontos érték, amely megegyezik a megadott karakterlánc által ábrázolt számmal.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metódus




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott karakterláncot, amely egy szám szöveges ábrázolását tartalmazza, az ekvivalens egypontos lebegőpontos értékre a megadott formázási információk és számstílus felhasználásával.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt típusú értékek bitenkénti kombinációja, amely meghatározza a szám karakterlánc ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációkat tartalmazza. |

### Visszatérési érték

Az egyetlen pontosságú lebegőpontos érték, amely megegyezik a megadott karakterlánc által ábrázolt számmal.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* osztály [String](../../string/)
* osztály [IFormatProvider](../../iformatprovider/)
* osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* névterület [System](../../)
* Library [Aspose.Slides](../../../)