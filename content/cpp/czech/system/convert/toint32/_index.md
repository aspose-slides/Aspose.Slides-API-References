---
title: ToInt32()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převede zadanou hodnotu typu boolean na ekvivalentní 32-bitové podepsané celé číslo.
type: docs
weight: 157
url: /cs/system/convert/toint32/
---
## Convert::ToInt32(bool) method

Převede zadanou hodnotu typu boolean na ekvivalentní 32-bitové podepsané celé číslo.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```
## Convert::ToInt32(uint8_t) method

Převede zadané 8-bitové unsigned integer na ekvivalentní 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```
## Convert::ToInt32(int8_t) method

Převede zadané 8-bitové signed integer na ekvivalentní 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```
## Convert::ToInt32(uint16_t) method

Převede zadané 16-bitové unsigned integer na ekvivalentní 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```
## Convert::ToInt32(int16_t) method

Převede zadané 16-bitové signed integer na ekvivalentní 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```
## Convert::ToInt32(uint32_t) method

Převede zadané 32-bitové unsigned integer na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```
## Convert::ToInt32(int32_t) method

Vrací zadané 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```
## Convert::ToInt32(uint64_t) method

Převede zadané 64-bitové unsigned integer na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```
## Convert::ToInt32(int64_t) method

Převede zadané 64-bitové signed integer na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(int64_t value)
```
## Convert::ToInt32(float) method

Převede zadané číslo typu float na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(float value)
```
## Convert::ToInt32(double) method

Převede zadané číslo typu double na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(double value)
```
## Convert::ToInt32(const Decimal\&) method

Převede zadané desetinné číslo typu Decimal na ekvivalentní 32-bitové signed integer.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```
## Convert::ToInt32(char_t) method

Převede zadaný unicode znak na ekvivalentní 32-bitové signed integer.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```
## Convert::ToInt32(DateTime) method

Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```
## Convert::ToInt32(std::nullptr_t) method

Převede zadaný null-string na ekvivalentní 32-bitovou celočíselnou hodnotu.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Návratová hodnota

Nula.

## Convert::ToInt32(const char_t *) method

Převede zadaný c-string obsahující řetězcovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | c-string k převodu |

### Návratová hodnota

32-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným c-stringem

## Convert::ToInt32(const String\&) method

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

32-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToInt32(const String\&, int) method

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla v zadaném číselném systému na ekvivalentní 32-bitovou celočíselnou hodnotu.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ číselného systému, ve kterém je číslo v řetězci reprezentováno |

### Návratová hodnota

32-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

32-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) method




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Převede zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní 32-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl řetězcové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

32-bitová celočíselná hodnota odpovídající číslu reprezentovanému zadaným řetězcem

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) method




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Převede zadanou zabalenou hodnotu na ekvivalentní 32-bitovou celočíselnou hodnotu.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

32-bitová celočíselná hodnota ekvivalentní zadané zabalené hodnotě

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