---
title: TryParse()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 64 bites előjeles egész számmá.
type: docs
weight: 14
url: /hu/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 64 bites előjeles egész számmá.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| result | **int64_t**\& | Az a hivatkozás egy 64 bites előjeles egész változóra, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) metódus


Átalakítja a megadott karakterláncot, amely egy szám karakteres ábrázolását tartalmazza, a megfelelő 64 bites előjeles egész számmá a megadott formázási információk és számstílus felhasználásával.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formátum információkat tartalmazza. |
| result | **int64_t**\& | Az a hivatkozás egy 64 bites előjeles egész változóra, ahová a konverzió eredménye kerül. |

### Visszatérési érték

True, ha a konverzió sikeres, egyébként - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) metódus




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) metódus




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) metódus




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Int64](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)