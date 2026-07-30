---
title: ToDouble()
second_title: Aspose.Slides pro C++ - reference API
description: Převede zadanou hodnotu typu boolean na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.
type: docs
weight: 222
url: /cs/system/convert/todouble/
---
## Convert::ToDouble(bool) metoda


Převede zadanou hodnotu typu boolean na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metoda


Převede zadané 8-bitové celé číslo bez znaménka na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metoda


Převede zadané 8-bitové celé číslo se znaménkem na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metoda


Převede zadané 16-bitové celé číslo bez znaménka na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metoda


Převede zadané 16-bitové celé číslo se znaménkem na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metoda


Převede zadané 32-bitové celé číslo bez znaménka na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metoda


Převede zadané 32-bitové celé číslo se znaménkem na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metoda


Převede zadané 64-bitové celé číslo bez znaménka na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metoda


Převede zadané 64-bitové celé číslo se znaménkem na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metoda


Převede zadané číslo s jednoduchou přesností na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metoda


Vrátí zadané číslo typu double.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metoda


Převede zadané desetinné číslo na ekvivalentní číslo s dvojitou přesností v plovoucí řádové čárce.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metoda


Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metoda


Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metoda


Převede zadaný null-string na ekvivalentní hodnotu typu double.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Návratová hodnota

Nula.

## Convert::ToDouble(const char_t *) metoda


Převede zadaný c-string obsahující číselnou reprezentaci na ekvivalentní hodnotu typu double.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | C-string určený k převodu |

### Návratová hodnota

Číslo s dvojitou přesností rovné číslu představovanému zadaným c-stringem

## Convert::ToDouble(const String\&) metoda


Převede zadaný string obsahující číselnou reprezentaci na ekvivalentní hodnotu typu double.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String určený k převodu |

### Návratová hodnota

Číslo s dvojitou přesností rovné číslu představovanému zadaným stringem

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný string obsahující číselnou reprezentaci na ekvivalentní hodnotu typu double pomocí poskytnutých formátovacích informací.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String určený k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce |

### Návratová hodnota

Číslo s dvojitou přesností rovné číslu představovanému zadaným stringem

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metoda




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný string obsahující číselnou reprezentaci na ekvivalentní hodnotu typu double pomocí poskytnutých formátovacích informací a stylu čísla.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String určený k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl číselné reprezentace |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce |

### Návratová hodnota

Číslo s dvojitou přesností rovné číslu představovanému zadaným stringem

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadanou zabalenou hodnotu na číslo typu double. Pokud je typ zabalené hodnoty [String](../../string/), použije se při převodu zadaný formát řetězce.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který hodnotu zabaluje |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Číslo s dvojitou přesností ekvivalentní zadané zabalené hodnotě

## Viz také

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