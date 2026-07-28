---
title: TryParse()
second_title: Aspose.Slides C++ API Referenciája
description: Átalakítja a megadott, egy szám karakterlánc ábrázolását tartalmazó karakterláncot a megfelelő 16 bites előjeles egész számmá.
type: docs
weight: 14
url: /hu/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metódus


Converts the specified string containing the string representation of a number to the equivalent 16-bit signed integer.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| result | **int16_t**\& | A 16 bites előjeles egész változó referencia, amelybe a konvertálás eredménye kerül. |

### Visszatérési érték

True, ha a konvertálás sikeres, egyébként - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metódus


Converts the specified string containing the string representation of a number to the equivalent 16-bit signed integer using the provided formatting information and number style.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám karakterlánc ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy objektumra mutató pointer, amely a karakterlánc formázási információit tartalmazza. |
| result | **int16_t**\& | A 16 bites előjeles egész változó referencia, amelybe a konvertálás eredménye kerül. |

### Visszatérési érték

True, ha a konvertálás sikeres, egyébként - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metódus




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metódus




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metódus




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)