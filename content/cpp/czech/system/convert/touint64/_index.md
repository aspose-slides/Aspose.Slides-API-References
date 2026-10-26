---
title: ToUInt64()
second_title: Referenční příručka API Aspose.Slides pro C++
description: Převádí zadanou logickou hodnotu na ekvivalentní 64bitové nezáporné celé číslo.
type: docs
weight: 196
url: /cs/system/convert/touint64/
---
## Convert::ToUInt64(bool) metoda

Převádí zadanou logickou hodnotu na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metoda

Převádí zadané 8bitové nezáporné celé číslo na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metoda

Převádí zadané 8bitové celé číslo se znaménkem na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metoda

Převádí zadané 16bitové nezáporné celé číslo na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metoda

Převádí zadané 16bitové celé číslo se znaménkem na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metoda

Převádí zadané 32bitové nezáporné celé číslo na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metoda

Převádí zadané 32bitové celé číslo se znaménkem na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metoda

Vrací zadané 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metoda

Převádí zadané 64bitové celé číslo se znaménkem na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metoda

Převádí zadané číslo typu float na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metoda

Převádí zadané číslo typu double na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metoda

Převádí zadané desetinné číslo na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metoda

Převádí zadaný unicode znak na ekvivalentní 64bitové nezáporné celé číslo.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metoda

Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metoda

Převádí zadaný null-string na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToUInt64(const char_t *) metoda

Převádí zadaný c-string obsahující řetězcovou reprezentaci čísla na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | c-string k převodu |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota rovná číslu reprezentovanému zadaným c-stringem

## Convert::ToUInt64(const String\&) metoda

Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt64(const String\&, int) metoda

Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla v zadaném základu na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ čísla reprezentovaného řetězcem |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl řetězcové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metoda

```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadanou zabalenou hodnotu na ekvivalentní nezápornou 64bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Nezáporná 64bitová celočíselná hodnota ekvivalentní zadané zabalené hodnotě

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