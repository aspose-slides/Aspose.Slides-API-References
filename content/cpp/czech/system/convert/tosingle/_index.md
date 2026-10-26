---
title: ToSingle()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadanou logickou hodnotu na ekvivalentní číslo s jednoduchou přesností.
type: docs
weight: 209
url: /cs/system/convert/tosingle/
---
## Convert::ToSingle(bool) metoda

Převádí zadanou hodnotu typu bool na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metoda

Převádí zadané 8-bitové neoznačené celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metoda

Převádí zadané 8-bitové podepsané celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metoda

Převádí zadané 16-bitové neoznačené celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metoda

Převádí zadané 16-bitové podepsané celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metoda

Převádí zadané 32-bitové neoznačené celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metoda

Převádí zadané 32-bitové podepsané celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metoda

Převádí zadané 64-bitové neoznačené celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metoda

Převádí zadané 64-bitové podepsané celé číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metoda

Vrací zadané číslo typu float.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metoda

Převádí zadané číslo dvojité přesnosti na ekvivalentní číslo s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metoda

Převádí zadané desetinné číslo na ekvivalentní číslo s jednoduchou přesností.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metoda

Konverze není podporována. Vždy vyvolá výjimku InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metoda

Konverze není podporována. Vždy vyvolá výjimku InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metoda

Převádí zadaný nulový řetězec na ekvivalentní hodnotu s jednoduchou přesností.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToSingle(const char_t *) metoda

Převádí zadaný c-string obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | c-string k převodu |

### Návratová hodnota

Hodnota s jednoduchou přesností rovná číslu reprezentovanému zadaným c-stringem

## Convert::ToSingle(const String\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

Hodnota s jednoduchou přesností rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností pomocí poskytnutých informací o formátování.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

Hodnota s jednoduchou přesností rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metoda

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s jednoduchou přesností pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

Hodnota s jednoduchou přesností rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadanou zabalenou hodnotu na číslo s jednoduchou přesností.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Číslo s jednoduchou přesností ekvivalentní zadané zabalené hodnotě

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [Decimal](../../decimal/)
* Třída [DateTime](../../datetime/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Třída [Object](../../object/)
* Struktura [Convert](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)