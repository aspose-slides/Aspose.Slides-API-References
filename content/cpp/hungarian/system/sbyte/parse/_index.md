---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjeles egész számra.
type: docs
weight: 1
url: /hu/system/sbyte/parse/
---
## SByte::Parse(const String\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjeles egész számra.

```cpp
static int8_t System::SByte::Parse(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |

### Visszatérési érték

A megadott karakterlánc által ábrázolt számnak megfelelő 8 bites előjeles egész szám.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjeles egész számra a megadott formázási információk használatával.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációt tartalmazza. |

### Visszatérési érték

A megadott karakterlánc által ábrázolt számnak megfelelő 8 bites előjeles egész szám.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 8 bites előjeles egész számra a megadott formázási információk és számstílus használatával.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a karakterlánc formátuminformációt tartalmazza. |

### Visszatérési érték

A megadott karakterlánc által ábrázolt számnak megfelelő 8 bites előjeles egész szám.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)