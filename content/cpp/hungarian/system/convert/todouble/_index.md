---
title: ToDouble()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott logikai értéket egyenértékű dupla pontosságú lebegőpontos számmá.
type: docs
weight: 222
url: /hu/system/convert/todouble/
---
## Convert::ToDouble(bool) metódus

Az adott logikai értéket egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metódus

A megadott 8 bites előjel nélküli egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metódus

A megadott 8 bites előjeles egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metódus

A megadott 16 bites előjel nélküli egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metódus

A megadott 16 bites előjeles egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metódus

A megadott 32 bites előjel nélküli egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metódus

A megadott 32 bites előjeles egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metódus

A megadott 64 bites előjel nélküli egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metódus

A megadott 64 bites előjeles egész számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metódus

A megadott egyszeres pontosságú számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metódus

Visszaadja a megadott double számot.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metódus

A megadott decimal számot egyenértékű dupla pontosságú lebegőpontos számmá konvertálja.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metódus

A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metódus

A megadott null karakterláncot egyenértékű dupla pontosságú lebegőpontos értékké konvertálja.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Visszatérési érték

Zero.

## Convert::ToDouble(const char_t *) metódus

A megadott c-stringet, amely egy szám karakteres ábrázolását tartalmazza, egyenértékű dupla pontosságú lebegőpontos értékké konvertálja.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | Az átalakítandó c-string |

### Visszatérési érték

A megadott c-string által ábrázolt számnak megfelelő dupla pontosságú lebegőpontos érték

## Convert::ToDouble(const String\&) metódus


A megadott stringet, amely egy szám karakteres ábrázolását tartalmazza, egyenértékű dupla pontosságú lebegőpontos értékké konvertálja.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó string |

### Visszatérési érték

A megadott string által ábrázolt számnak megfelelő dupla pontosságú lebegőpontos érték

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


A megadott stringet, amely egy szám karakteres ábrázolását tartalmazza, a megadott formázási információk felhasználásával egyenértékű dupla pontosságú lebegőpontos értékké konvertálja.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a string formátuminformációt tartalmazza |

### Visszatérési érték

A megadott string által ábrázolt számnak megfelelő dupla pontosságú lebegőpontos érték

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metódus




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


A megadott stringet, amely egy szám karakteres ábrázolását tartalmazza, a megadott formázási információk és számformátum (NumberStyles) felhasználásával egyenértékű dupla pontosságú lebegőpontos értékké konvertálja.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | Az átalakítandó string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékeinek bitenkénti kombinációja, amely meghatározza a szám karakteres ábrázolásának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a string formátuminformációt tartalmazza |

### Visszatérési érték

A megadott string által ábrázolt számnak megfelelő dupla pontosságú lebegőpontos érték

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


A megadott dobozolt értéket dupla pontosságú lebegőpontos értékké konvertálja. Ha a dobozolt érték típusa [String](../../string/), akkor a megadott string formátumot használja a konverzió során.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor használ a konverzió, ha a dobozolt érték típusa [String](../../string/) |

### Visszatérési érték

A megadott dobozolt értéknek megfelelő dupla pontosságú lebegőpontos érték

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)