---
title: Parse()
second_title: Aspose.Slides pro C++ API Referenci
description: Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8bitové celé číslo bez znaménka.
type: docs
weight: 1
url: /cs/system/byte/parse/
---
## Byte::Parse(const String\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8bitové celé číslo bez znaménka.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |

### Návratová hodnota

8bitové celé číslo bez znaménka odpovídající číslu reprezentovanému zadaným řetězcem.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8bitové celé číslo bez znaménka pomocí poskytnutých informací o formátování.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

8bitové celé číslo bez znaménka odpovídající číslu reprezentovanému zadaným řetězcem.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 8bitové celé číslo bez znaménka pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

8bitové celé číslo bez znaménka odpovídající číslu reprezentovanému zadaným řetězcem.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Výčet [NumberStyles](../../../system.globalization/numberstyles/)
* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [Byte](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Obor názvů [System](../../)
* Knihovna [Aspose.Slides](../../../)