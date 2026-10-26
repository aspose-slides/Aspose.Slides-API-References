---
title: ToByte()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadanou logickou hodnotu na ekvivalentní 8-bitové bezeznačkové celé číslo.
type: docs
weight: 92
url: /cs/system/convert/tobyte/
---
## Convert::ToByte(bool) metoda

Převádí zadanou logickou hodnotu na ekvivalentní 8-bitové bezeznačkové celé číslo.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) metoda

Vrací zadané 8-bitové bezeznačkové celé číslo.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) metoda

Převádí zadané 8-bitové podepsané celé číslo na ekvivalentní 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) metoda

Převádí zadané 16-bitové bezeznačkové celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) metoda

Převádí zadané 16-bitové podepsané celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) metoda

Převádí zadané 32-bitové bezeznačkové celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) metoda

Převádí zadané 32-bitové podepsané celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) metoda

Převádí zadané 64-bitové bezeznačkové celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) metoda

Převádí zadané 64-bitové podepsané celé číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) metoda

Převádí zadané číslo typu float na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) metoda

Převádí zadané číslo typu double na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) metoda

Převádí zadané desetinné číslo na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) metoda

Převádí zadaný Unicode znak na ekvální 8-bitové bezeznačkové celé číslo.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) metoda

Převod není podporován. Vždy vyhodí InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) metoda

Převádí zadaný null-string na odpovídající bezeznačkovou 8-bitovou celočíselnou hodnotu.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToByte(const char_t *) metoda

Převádí zadaný c-string, který obsahuje řetězcovou reprezentaci čísla, na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | c-string k převodu |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným c-stringem

## Convert::ToByte(const String\&) metoda

Převádí zadaný řetězec, který obsahuje řetězcovou reprezentaci čísla, na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToByte(const String\&, int) metoda

Převádí zadaný řetězec, který obsahuje řetězcovou reprezentaci čísla v zadané soustavě, na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ číselné soustavy řetězce |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec, který obsahuje řetězcovou reprezentaci čísla, na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec, který obsahuje řetězcovou reprezentaci čísla, na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot enumerace NumberStyles, která určuje povolený styl řetězcové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) metoda

```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadanou zabalenou (boxed) hodnotu na ekvální bezeznačkovou 8-bitovou celočíselnou hodnotu.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který balí hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Bezeznačková 8-bitová celočíselná hodnota ekvivalentní zadané zabalené hodnotě

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)