---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo.
type: docs
weight: 1
url: /cs/system/int16/parse/
---
## Int16::Parse(const String\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo.

```cpp
static int16_t System::Int16::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |

### Návratová hodnota

16-bitové podepsané celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo pomocí poskytnutých informací o formátování.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

16-bitové podepsané celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové podepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot NumberStyles enum, která specifikuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

16-bitové podepsané celé číslo rovné číslu reprezentovanému zadaným řetězcem.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)