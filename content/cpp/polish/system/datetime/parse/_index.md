---
title: Parse()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Konwertuje podaną reprezentację łańcucha daty i czasu na równoważny obiekt DateTime.
type: docs
weight: 859
url: /pl/system/datetime/parse/
---
## DateTime::Parse(const String\&) metoda

Konwertuje podaną reprezentację łańcucha daty i czasu na równoważny obiekt [DateTime](../).

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha daty i czasu do konwersji. |

### Wartość zwracana

Nowa instancja klasy [DateTime](../), która reprezentuje wartość daty i czasu równoważną tej przedstawionej w podanym łańcuchu.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Konwertuje podaną reprezentację łańcucha daty i czasu na równoważny obiekt [DateTime](../) przy użyciu informacji o formacie zależnym od kultury.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja łańcucha daty i czasu do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/) zapewniający informacje o formacie zależnym od kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitowa kombinacja wartości wyliczeniowych, które dostarczają dodatkowych informacji o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji **s** do obiektu [DateTime](../). |

### Wartość zwracana

Nowa instancja klasy [DateTime](../), która reprezentuje wartość daty i czasu równoważną tej przedstawionej w podanym łańcuchu.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metoda

```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Zobacz także

* Wyliczenie [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [DateTime](../)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)