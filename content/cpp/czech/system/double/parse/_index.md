---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností.
type: docs
weight: 1
url: /cs/system/double/parse/
---
## Double::Parse(const String\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností.

```cpp
static double System::Double::Parse(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |

### Návratová hodnota

Hodnota s dvojitou přesností, která odpovídá číslu reprezentovanému zadaným řetězcem.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností pomocí poskytnutých informací o formátování.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězců. |

### Návratová hodnota

Hodnota s dvojitou přesností, která odpovídá číslu reprezentovanému zadaným řetězcem.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) metoda




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězců. |

### Návratová hodnota

Hodnota s dvojitou přesností, která odpovídá číslu reprezentovanému zadaným řetězcem.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktura [Double](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)