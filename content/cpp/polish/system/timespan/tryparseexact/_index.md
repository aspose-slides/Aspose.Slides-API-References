---
title: TryParseExact()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Konwertuje łańcuch na równoważny obiekt TimeSpan przy użyciu określonych formatów i dostawcy formatu, i zwraca wynik konwersji.
type: docs
weight: 573
url: /pl/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method

Konwertuje łańcuch na równoważny obiekt [TimeSpan](../) przy użyciu określonych formatów i dostawcy formatu oraz zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) ciągów formatu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu, który dostarcza informacje formatowania specyficzne dla kultury. |
| result | [TimeSpan](../)\& | Interwał czasu odpowiadający łańcuchowi. |

### Wartość zwracana

True, jeśli łańcuch został pomyślnie skonwertowany; w przeciwnym razie false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method

Konwertuje łańcuch na równoważny obiekt [TimeSpan](../) przy użyciu określonego formatu, dostawcy formatu i stylów oraz zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |
| format | const [String](../../string/)\& | Standardowy lub niestandardowy ciąg formatu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu, który dostarcza informacje formatowania specyficzne dla kultury. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definiuje elementy, które mogą występować w łańcuchu wejściowym. |
| result | [TimeSpan](../)\& | Interwał czasu odpowiadający łańcuchowi. |

### Wartość zwracana

True, jeśli łańcuch został pomyślnie skonwertowany; w przeciwnym razie false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method

Konwertuje łańcuch na równoważny obiekt [TimeSpan](../) przy użyciu określonych formatów, dostawcy formatu i stylów oraz zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) ciągów formatu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu, który dostarcza informacje formatowania specyficzne dla kultury. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definiuje elementy, które mogą występować w łańcuchu wejściowym. |
| result | [TimeSpan](../)\& | Interwał czasu odpowiadający łańcuchowi. |

### Wartość zwracana

True, jeśli łańcuch został pomyślnie skonwertowany; w przeciwnym razie false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method

Konwertuje łańcuch na równoważny obiekt [TimeSpan](../) przy użyciu określonego formatu i dostawcy formatu oraz zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |
| format | const [String](../../string/)\& | Standardowy lub niestandardowy ciąg formatu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu, który dostarcza informacje formatowania specyficzne dla kultury. |
| result | [TimeSpan](../)\& | Interwał czasu odpowiadający łańcuchowi. |

### Wartość zwracana

True, jeśli łańcuch został pomyślnie skonwertowany; w przeciwnym razie false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Zobacz także

* Wyliczenie [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Definicja typu [ArrayPtr](../../arrayptr/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [TimeSpan](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)