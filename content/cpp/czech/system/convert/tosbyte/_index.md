---
title: ToSByte()
second_title: Aspose.Slides pro C++ – reference API
description: Převede zadanou logickou hodnotu na odpovídající 8bitové celé číslo se znaménkem.
type: docs
weight: 105
url: /cs/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metoda

Převede zadanou logickou hodnotu na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) metoda

Převede zadané 8bitové nezáporné celé číslo na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) metoda

Vrací zadané 8bitové celé číslo se znaménkem.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) metoda

Převede zadané 16bitové nezáporné celé číslo na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) metoda

Převede zadané 16bitové celé číslo se znaménkem na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) metoda

Převede zadané 32bitové nezáporné celé číslo na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) metoda

Převede zadané 32bitové celé číslo se znaménkem na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) metoda

Převede zadané 64bitové nezáporné celé číslo na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) metoda

Převede zadané 64bitové celé číslo se znaménkem na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) metoda

Převede zadané číslo typu float na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) metoda

Převede zadané číslo typu double na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) metoda

Převede zadané desetinné číslo na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) metoda

Převede zadaný znak Unicode na odpovídající 8bitové celé číslo se znaménkem.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) metoda

Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) metoda

Převede zadaný nulový řetězec na odpovídající 8bitovou celočíselnou hodnotu.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToSByte(const char_t *) metoda

Převede zadaný C-řetězec obsahující textovou reprezentaci čísla na odpovídající 8bitovou celočíselnou hodnotu.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-řetězec, který se má převést |

### Návratová hodnota

8bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným C-řetězcem

## Convert::ToSByte(const String\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 8bitovou celočíselnou hodnotu.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |

### Návratová hodnota

8bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToSByte(const String\&, int) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla v zadaném základu na odpovídající 8bitovou celočíselnou hodnotu.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| from_base | int | Základ čísla reprezentovaného řetězcem |

### Návratová hodnota

8bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající nezápornou 8bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

8bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 8bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

Nezáporná 8bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metoda

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadanou zabalenou hodnotu na odpovídající 8bitovou celočíselnou hodnotu.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

8bitová celočíselná hodnota odpovídající zadané zabalené hodnotě

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