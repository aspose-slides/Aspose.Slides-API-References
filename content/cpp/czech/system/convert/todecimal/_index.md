---
title: ToDecimal()
second_title: Aspose.Slides pro C++ – reference API
description: Převede zadanou hodnotu typu boolean na ekvivalentní desítkové číslo.
type: docs
weight: 235
url: /cs/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metoda

Převede zadanou hodnotu typu bool na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metoda

Převede zadané 8-bitové nezáporné celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metoda

Převede zadané 8-bitové podepsané celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metoda

Převede zadané 16-bitové nezáporné celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metoda

Převede zadané 16-bitové podepsané celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metoda

Převede zadané 32-bitové nezáporné celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metoda

Převede zadané 32-bitové podepsané celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metoda

Převede zadané 64-bitové nezáporné celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metoda

Převede zadané 64-bitové podepsané celé číslo na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metoda

Převede zadané číslo typu float na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metoda

Převede zadané číslo typu double na ekvivalentní desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metoda

Vrátí zadané desítkové číslo.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metoda

Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metoda

Převede zadaný null-string na ekvivalentní hodnotu [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToDecimal(const char_t *) metoda

Převede zadaný c-string obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | c-string k převodu |

### Návratová hodnota

Hodnota [Decimal](../../decimal/) rovná číslu, které představuje zadaný c-string

## Convert::ToDecimal(const String\&) metoda

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

Hodnota [Decimal](../../decimal/) rovná číslu, které představuje zadaný řetězec

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../../decimal/) pomocí poskytnutých informací o formátování.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

Hodnota [Decimal](../../decimal/) rovná číslu, které představuje zadaný řetězec

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](../../decimal/) pomocí zadaných stylů čísel a informací o formátování.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl řetězcové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

Hodnota [Decimal](../../decimal/) rovná číslu, které představuje zadaný řetězec

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadanou zabalenou hodnotu na ekvivalentní hodnotu [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Hodnota [Decimal](../../decimal/) ekvivalentní zadané zabalené hodnotě

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)