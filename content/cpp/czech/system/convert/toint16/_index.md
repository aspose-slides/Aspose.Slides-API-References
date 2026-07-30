---
title: ToInt16()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadanou logickou hodnotu na ekvivalentní 16-bitové celočíselné číslo se znaménkem.
type: docs
weight: 131
url: /cs/system/convert/toint16/
---
## Convert::ToInt16(bool) metoda

Převádí zadanou logickou hodnotu na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) metoda

Převádí zadané 8-bitové neznačkové celé číslo na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) metoda

Převádí zadané 8-bitové celočíselné číslo se znaménkem na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) metoda

Převádí zadané 16-bitové neznačkové celé číslo na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) metoda

Vrací zadané 16-bitové celočíselné číslo se znaménkem.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) metoda

Převádí zadané 32-bitové neznačkové celé číslo na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) metoda

Převádí zadané 32-bitové celočíselné číslo se znaménkem na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) metoda

Převádí zadané 64-bitové neznačkové celé číslo na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) metoda

Převádí zadané 64-bitové celočíselné číslo se znaménkem na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) metoda

Převádí zadané číslo typu float na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) metoda

Převádí zadané číslo typu double na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) metoda

Převádí zadané desetinné číslo na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) metoda

Převádí zadaný znak Unicode na ekvivalentní 16-bitové celočíselné číslo se znaménkem.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) metoda

Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) metoda

Převádí zadaný nulový řetězec na ekvivalentní 16-bitovou celočíselnou hodnotu.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Návratová hodnota

Nula.

## Convert::ToInt16(const char_t *) metoda

Převádí zadaný C-řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitovou celočíselnou hodnotu.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-řetězec k převodu |

### Návratová hodnota

16-bitová celočíselná hodnota rovná číslu reprezentovanému zadaným C-řetězcem

## Convert::ToInt16(const String\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitovou celočíselnou hodnotu.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

16-bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToInt16(const String\&, int) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla v určeném základu na ekvivalentní 16-bitovou celočíselnou hodnotu.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ čísla reprezentovaného řetězcem |

### Návratová hodnota

16-bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

16-bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitovou celočíselnou hodnotu pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce |

### Návratová hodnota

16-bitová celočíselná hodnota rovná číslu reprezentovanému zadaným řetězcem

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metoda 




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí zadanou zabalenou hodnotu na ekvivalentní 16-bitovou celočíselnou hodnotu.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

16-bitová celočíselná hodnota ekvivalentní zadané zabalené hodnotě

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