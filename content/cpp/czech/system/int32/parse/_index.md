---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32bitové celé číslo se znaménkem.
type: docs
weight: 1
url: /cs/system/int32/parse/
---
## Int32::Parse(const String\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32bitové celé číslo se znaménkem.

```cpp
static int32_t System::Int32::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |

### Návratová hodnota

32bitové celé číslo se znaménkem rovnající se číslu představovanému zadaným řetězcem.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32bitové celé číslo se znaménkem pomocí poskytnutých informací o formátování.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

32bitové celé číslo se znaménkem rovnající se číslu představovanému zadaným řetězcem.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32bitové celé číslo se znaménkem pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

32bitové celé číslo se znaménkem rovnající se číslu představovanému zadaným řetězcem.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) metoda




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## Další informace

* Výčtový typ [NumberStyles](../../../system.globalization/numberstyles/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Int32](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Třída [ReadOnlySpan](../../readonlyspan/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)