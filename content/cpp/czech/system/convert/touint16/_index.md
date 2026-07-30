---
title: ToUInt16()
second_title: Aspose.Slides pro C++ – API Reference
description: Převádí zadanou logickou hodnotu na ekvivalentní 16-bitové nezáporné celé číslo.
type: docs
weight: 144
url: /cs/system/convert/touint16/
---
## Convert::ToUInt16(bool) metoda


Převádí zadanou logickou hodnotu na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```

## Convert::ToUInt16(uint8_t) metoda


Převádí zadané 8-bitové nezáporné celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```

## Convert::ToUInt16(int8_t) metoda


Převádí zadané 8-bitové podepsané celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```

## Convert::ToUInt16(uint16_t) metoda


Vrací zadané 16-bitové nezáporné celé číslo.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```

## Convert::ToUInt16(int16_t) metoda


Převádí zadané 16-bitové podepsané celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```

## Convert::ToUInt16(uint32_t) metoda


Převádí zadané 32-bitové nezáporné celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```

## Convert::ToUInt16(int32_t) metoda


Převádí zadané 32-bitové podepsané celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```

## Convert::ToUInt16(uint64_t) metoda


Převádí zadané 64-bitové nezáporné celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```

## Convert::ToUInt16(int64_t) metoda


Převádí zadané 64-bitové podepsané celé číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```

## Convert::ToUInt16(float) metoda


Převádí zadané číslo typu float na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```

## Convert::ToUInt16(double) metoda


Převádí zadané číslo typu double na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```

## Convert::ToUInt16(const Decimal\&) metoda


Převádí zadané desítkové číslo na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```

## Convert::ToUInt16(char_t) metoda


Převádí zadaný unicode znak na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```

## Convert::ToUInt16(DateTime) metoda


Konverze není podporována. Vždy vyvolá výjimku InvalidCastException.

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```

## Convert::ToUInt16(std::nullptr_t) metoda


Převádí zadaný null-string na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```


### Návratová hodnota

Nula.

## Convert::ToUInt16(const char_t *) metoda


Převádí zadaný c-string obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-string k převodu |

### Návratová hodnota

16-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným c-stringem

## Convert::ToUInt16(const String\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

16-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt16(const String\&, int) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla v zadané soustavě na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| from_base | int | Základ čísla reprezentovaného řetězcem |

### Návratová hodnota

16-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nezáporné celé číslo pomocí poskytnutých informací o formátování.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

16-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové nezáporné celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl řetězcové reprezentace čísla |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce |

### Návratová hodnota

16-bitové nezáporné celé číslo rovné číslu reprezentovanému zadaným řetězcem

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) metoda




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadanou zabalenou hodnotu na ekvivalentní 16-bitové nezáporné celé číslo.

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt zabalený hodnotou k převodu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

16-bitové nezáporné celé číslo ekvivalentní zadané zabalené hodnotě

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