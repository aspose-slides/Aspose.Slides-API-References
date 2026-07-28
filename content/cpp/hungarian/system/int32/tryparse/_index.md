---
title: TryParse()
second_title: Aspose.Slides C++ API Referenciája
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 32 bites előjeles egész számmá.
type: docs
weight: 14
url: /hu/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 32 bites előjeles egész számmá.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **int32_t**\& | A hivatkozás egy 32 bites előjeles egész változóra, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

True if the conversion succeeded, otherwise - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 32 bites előjeles egész számmá a megadott formázási információk és számstílus használatával.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formátuminformációit tartalmazza. |
| result | **int32_t**\& | A hivatkozás egy 32 bites előjeles egész változóra, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

True if the conversion succeeded, otherwise - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) metódus




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) metódus




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) metódus




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)