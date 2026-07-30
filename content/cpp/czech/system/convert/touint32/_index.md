---
title: ToUInt32()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí zadanou logickou hodnotu na ekvivalentní 32-bitové nezáporné celé číslo.
type: docs
weight: 170
url: /cs/system/convert/touint32/
---
## Convert::ToUInt32(bool) method

Převádí zadanou logickou hodnotu na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) method

Převádí zadané 8-bitové nezáporné celé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) method

Převádí zadané 8-bitové celistvé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) method

Převádí zadané 16-bitové nezáporné celé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) method

Převádí zadané 16-bitové celistvé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) method

Vracejí zadané 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) method

Převádí zadané 32-bitové celistvé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) method

Převádí zadané 64-bitové nezáporné celé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) method

Převádí zadané 64-bitové celistvé číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) method

Převádí zadané číslo typu float na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) method

Převádí zadané číslo typu double na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) method

Převádí zadané desetinné číslo na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) method

Převádí zadaný unicode znak na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) method

Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) method

Převádí zadaný null-string na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Návratová hodnota

Nula.

## Convert::ToUInt32(const char_t *) method

Převádí zadaný c-string obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-string, který se má převést |

### Návratová hodnota

32-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným c-stringem

## Convert::ToUInt32(const String\&) method

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |

### Návratová hodnota

32-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt32(const String\&, int) method

Převádí zadaný řetězec obsahující textovou reprezentaci čísla v zadaném základu na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| from_base | int | Základ čísla, ve kterém je řetězec reprezentován |

### Návratová hodnota

32-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezáporné celé číslo pomocí poskytnutých informací o formátování.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

32-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) method




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezáporné celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

32-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) method 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) method 




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Převádí zadanou zabalenou hodnotu na ekvivalentní 32-bitové nezáporné celé číslo.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

32-bitové nezáporné celé číslo ekvivalentní zadané zabalené hodnotě

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [Decimal](../../decimal/)
* Třída [DateTime](../../datetime/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Třída [Object](../../object/)
* Struktura [Convert](../)
* Struktura [Enum](../../enum/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)