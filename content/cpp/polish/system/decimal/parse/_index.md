---
title: Parse()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje reprezentację łańcucha liczby dziesiętnej na równoważną instancję klasy Decimal.
type: docs
weight: 469
url: /pl/system/decimal/parse/
---
## Decimal::Parse(const String\&) metoda

Konwertuje reprezentację łańcucha liczby dziesiętnej na równoważną instancję klasy [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha liczby |

### Wartość zwracana

Nowa instancja klasy [Decimal](../) reprezentująca wartość równoważną tej przedstawionej w podanym łańcuchu.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metoda

Konwertuje reprezentację łańcucha liczby dziesiętnej na równoważną instancję klasy [Decimal](../) przy użyciu określonego stylu.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha wartości dziesiętnej do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia, która dostarcza dodatkowych informacji o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** do obiektu [Decimal](../) |

### Wartość zwracana

Nowa instancja klasy [Decimal](../) reprezentująca wartość równoważną tej przedstawionej w podanym łańcuchu

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje reprezentację łańcucha liczby dziesiętnej na równoważną instancję klasy [Decimal](../) przy użyciu określonego dostawcy formatu.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha wartości dziesiętnej do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu |

### Wartość zwracana

Nowa instancja klasy [Decimal](../) reprezentująca wartość równoważną tej przedstawionej w podanym łańcuchu

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje reprezentację łańcucha liczby dziesiętnej na równoważną instancję klasy [Decimal](../) przy użyciu określonego stylu i dostawcy formatu.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha wartości dziesiętnej do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia, która dostarcza dodatkowych informacji o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** do obiektu [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu |

### Wartość zwracana

Nowa instancja klasy [Decimal](../) reprezentująca wartość równoważną tej przedstawionej w podanym łańcuchu

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)