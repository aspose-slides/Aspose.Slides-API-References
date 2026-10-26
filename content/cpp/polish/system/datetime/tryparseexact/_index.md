---
title: TryParseExact()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny obiekt DateTime, używając podanego formatu, informacji o formacie specyficznych dla kultury oraz stylu. Format łańcuchowego przedstawienia musi dokładnie odpowiadać podanemu formatowi.
type: docs
weight: 898
url: /pl/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles, DateTime&) metoda


Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny obiekt [DateTime](../) przy użyciu podanego formatu, informacji o formacie specyficznych dla kultury oraz stylu. Format łańcuchowego przedstawienia musi dokładnie odpowiadać podanemu formatowi.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)& | Reprezentacja łańcucha wartości daty i czasu do konwersji. |
| format | const [String](../../string/)& | Format łańcucha. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Obiekt [IFormatProvider](../../iformatprovider/) zapewniający informacje o formacie specyficzne dla kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitowa kombinacja wartości wyliczenia, która dostarcza dodatkowych informacji o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** do obiektu [DateTime](../). |
| result | [DateTime](../)& | Argument wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji. |

### Return Value

true, jeśli konwersja się powiedzie, w przeciwnym razie - false.

## DateTime::TryParseExact(const String&, const String&, const SharedPtr<Globalization::CultureInfo>&, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String&, const String&, const SharedPtr<Globalization::DateTimeFormatInfo>&, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String&, const String&, std::nullptr_t, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles, DateTime&) metoda


Konwertuje określone łańcuchowe przedstawienie wartości daty i czasu na równoważny obiekt [DateTime](../) przy użyciu podanych formatów, informacji o formacie specyficznych dla kultury oraz stylu. Format łańcuchowego przedstawienia musi dokładnie odpowiadać jednemu z podanych formatów.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)& | Reprezentacja łańcucha wartości daty i czasu do konwersji. |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | Tablica formatów łańcuchowych. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Obiekt [IFormatProvider](../../iformatprovider/) zapewniający informacje o formacie specyficzne dla kultury. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Bitowa kombinacja wartości wyliczenia, która dostarcza dodatkowych informacji o **s**, o elementach stylu, które mogą występować w **s**, lub o konwersji z **s** do obiektu [DateTime](../). |
| result | [DateTime](../)& | Argument wyjściowy, który w przypadku pomyślnej konwersji zawiera wynik konwersji. |

### Return Value

true, jeśli konwersja się powiedzie, w przeciwnym razie - false.

## DateTime::TryParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<Globalization::CultureInfo>&, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<Globalization::DateTimeFormatInfo>&, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String&, const ArrayPtr<String>&, std::nullptr_t, Globalization::DateTimeStyles, DateTime&) metoda




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [DateTime](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)