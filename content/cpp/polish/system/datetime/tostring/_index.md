---
title: ToString()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca tekstową reprezentację wartości daty i czasu reprezentowanej przez bieżący obiekt, używając konwencji formatowania zdefiniowanych przez bieżącą kulturę.
type: docs
weight: 482
url: /pl/system/datetime/tostring/
---
## DateTime::ToString() const metoda

Zwraca reprezentację w postaci łańcucha znaków wartości daty i czasu reprezentowanej przez bieżący obiekt, używając konwencji formatowania zdefiniowanych przez bieżącą kulturę.

```cpp
String System::DateTime::ToString() const
```

### Wartość zwracana

Reprezentacja w postaci łańcucha znaków wartości reprezentowanej przez bieżący obiekt

## DateTime::ToString(const String\&) const metoda

Zwraca reprezentację w postaci łańcucha znaków wartości daty i czasu reprezentowanej przez bieżący obiekt, używając określonego formatu oraz konwencji formatowania zdefiniowanych przez bieżącą kulturę.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Ciąg formatu |

### Wartość zwracana

Reprezentacja w postaci łańcucha znaków wartości reprezentowanej przez bieżący obiekt, sformatowana zgodnie z formatem określonym przez **format** oraz bieżącą kulturę.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metoda

Zwraca reprezentację w postaci łańcucha znaków wartości daty i czasu reprezentowanej przez bieżący obiekt, używając podanych informacji o formacie.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt reprezentujący informacje o formacie |

### Wartość zwracana

Reprezentacja w postaci łańcucha znaków wartości reprezentowanej przez bieżący obiekt, sformatowana zgodnie z informacjami o formacie dostarczonymi przez **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metoda

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metoda

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metoda

```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda

Zwraca reprezentację w postaci łańcucha znaków wartości daty i czasu reprezentowanej przez bieżący obiekt, używając podanych informacji o formacie.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Ciąg formatu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt reprezentujący informacje o formacie |

### Wartość zwracana

Reprezentacja w postaci łańcucha znaków wartości reprezentowanej przez bieżący obiekt, sformatowana zgodnie z informacjami o formacie dostarczonymi przez **provider** oraz ciągiem formatu **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metoda

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metoda

```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [DateTime](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)