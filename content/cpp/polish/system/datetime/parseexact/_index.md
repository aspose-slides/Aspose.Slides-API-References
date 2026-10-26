---
title: ParseExact()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje określoną reprezentację ciągu znaków wartości daty i czasu na równoważny obiekt DateTime przy użyciu określonego formatu i informacji o formacie zależnym od kultury. Format reprezentacji ciągu musi dokładnie odpowiadać określonemu formatowi. Rzuca wyjątek, jeśli konwersja się nie powiedzie.
type: docs
weight: 872
url: /pl/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda


Konwertuje określoną reprezentację ciągu znaków wartości daty i czasu na równoważny obiekt [DateTime](../) przy użyciu określonego formatu i informacji o formacie zależnym od kultury. Format reprezentacji ciągu musi dokładnie odpowiadać określonemu formatowi. Rzuca wyjątek, jeśli konwersja się nie powiedzie.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja ciągu znaków wartości daty i czasu do konwersji. |
| format | const [String](../../string/)\& | Format ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/) zapewniający informacje o formacie zależnym od kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Połączenie bitowe wartości wyliczenia, które zapewnia dodatkowe informacje o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** na obiekt [DateTime](../). |

### Wartość zwracana

Nowa instancja klasy [DateTime](../) reprezentująca wartość daty i czasu równoważną tej przedstawionej w określonym ciągu znaków.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda


Konwertuje określoną reprezentację ciągu znaków wartości daty i czasu na równoważny obiekt [DateTime](../) przy użyciu określonych formatów, informacji o formacie zależnym od kultury oraz stylu. Format reprezentacji ciągu musi dokładnie odpowiadać jednemu lub kilku określonym formatom. Rzuca wyjątek, jeśli konwersja się nie powiedzie.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Reprezentacja ciągu znaków wartości daty i czasu do konwersji. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Tablica formatów ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/) zapewniający informacje o formacie zależnym od kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Połączenie bitowe wartości wyliczenia, które zapewnia dodatkowe informacje o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** na obiekt [DateTime](../). |

### Wartość zwracana

Nowa instancja klasy [DateTime](../) reprezentująca wartość daty i czasu równoważną tej przedstawionej w określonym ciągu znaków.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metoda




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Zobacz także

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)