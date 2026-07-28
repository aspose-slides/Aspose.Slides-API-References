---
title: TryParse()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny obiekt DateTime.
type: docs
weight: 885
url: /pl/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metoda


Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny [DateTime](../) obiekt.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Łańcuchowe przedstawienie wartości daty i czasu do konwersji. |
| result | [DateTime](../)\& | Argument wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji. |

### Wartość zwracana

True jeśli konwersja się powiedzie, w przeciwnym razie - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metoda


Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny [DateTime](../) obiekt przy użyciu określonych informacji o formacie specyficznych dla kultury i stylu.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Łańcuchowe przedstawienie wartości daty i czasu do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/), który dostarcza informacje o formacie specyficzne dla kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitowa kombinacja wartości wyliczeniowych, która dostarcza dodatkowe informacje o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** do obiektu [DateTime](../). |
| result | [DateTime](../)\& | Argument wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji. |

### Wartość zwracana

True jeśli konwersja się powiedzie, w przeciwnym razie - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metoda




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metoda




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Zobacz także

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)