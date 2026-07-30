---
title: ToInt64()
second_title: Aspose.Slides pro C++ - dokumentace API
description: Převádí zadanou logickou hodnotu na ekvivalentní 64bitové celé číslo se znaménkem.
type: docs
weight: 183
url: /cs/system/convert/toint64/
---
## Convert::ToInt64(bool) metoda


Převádí zadanou logickou hodnotu na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metoda


Převádí zadané 8-bitové neznačené celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metoda


Převádí zadané 8-bitové celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metoda


Převádí zadané 16-bitové neznačené celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metoda


Převádí zadané 16-bitové celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metoda


Převádí zadané 32-bitové neznačené celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metoda


Převádí zadané 32-bitové celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metoda


Převádí zadané 64-bitové neznačené celé číslo na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metoda


Vrací zadané 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metoda


Převádí zadané číslo typu float na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metoda


Převádí zadané číslo typu double na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metoda


Převádí zadané číslo typu Decimal na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metoda


Převádí zadaný Unicode znak na ekvivalentní 64-bitové celé číslo se znaménkem.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metoda


Převod není podporován. Vždy vyvolá InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metoda


Převádí zadaný nulový řetězec na ekvivalentní 64-bitové celé číslo.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Return Value

Nula.

## Convert::ToInt64(const char_t *) metoda


Převádí zadaný c-string obsahující textové vyjádření čísla na ekvivalentní 64-bitové celé číslo.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | C-string k převodu |

### Return Value

64-bitové celé číslo odpovídající číslu představovanému zadaným c-stringem

## Convert::ToInt64(const String\&) metoda


Převádí zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní 64-bitové celé číslo.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Return Value

64-bitové celé číslo odpovídající číslu představovanému zadaným řetězcem

## Convert::ToInt64(const String\&, int) metoda


Převádí zadaný řetězec obsahující textové vyjádření čísla v zadané soustavě na ekvivalentní 64-bitové celé číslo.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ číselné soustavy řetězcem reprezentovaného čísla |

### Return Value

64-bitové celé číslo odpovídající číslu představovanému zadaným řetězcem

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní 64-bitové celé číslo pomocí poskytnutých informací o formátování.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce |

### Return Value

64-bitové celé číslo odpovídající číslu představovanému zadaným řetězcem

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textové vyjádření čísla na ekvivalentní 64-bitové celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot enumerace NumberStyles určující povolený styl textové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt obsahující informace o formátu řetězce |

### Return Value

64-bitové celé číslo odpovídající číslu představovanému zadaným řetězcem

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metoda 




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadanou zabalenou hodnotu na ekvivalentní 64-bitové celé číslo.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt, který zabaluje hodnotu k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Return Value

64-bitové celé číslo ekvivalentní zadané zabalené hodnotě

## See Also

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