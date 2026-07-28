---
title: ToSingle()
second_title: Aspose.Slides dla C++ – Referencja API
description: Konwertuje określoną wartość logiczną na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.
type: docs
weight: 209
url: /pl/system/convert/tosingle/
---
## Convert::ToSingle(bool) metoda

Konwertuje określoną wartość logiczną na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metoda

Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metoda

Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metoda

Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metoda

Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metoda

Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metoda

Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metoda

Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metoda

Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metoda

Zwraca określoną liczbę typu float.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metoda

Konwertuje określoną liczbę podwójnej precyzji na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metoda

Konwertuje określoną liczbę dziesiętną na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metoda

Konwertuje określony ciąg zerowy na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Wartość zwracana

Zero.

## Convert::ToSingle(const char_t *) metoda

Konwertuje określony ciąg znaków C zawierający reprezentację liczby na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | Ciąg znaków C do konwersji |

### Wartość zwracana

Liczba zmiennoprzecinkowa o pojedynczej precyzji równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSingle(const String\&) metoda

Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

Liczba zmiennoprzecinkowa o pojedynczej precyzji równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji przy użyciu podanych informacji o formatowaniu.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

Liczba zmiennoprzecinkowa o pojedynczej precyzji równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metoda

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony ciąg znaków zawierający reprezentację liczby na równoważną liczbę zmiennoprzecinkową o pojedynczej precyzji przy użyciu podanych informacji o formatowaniu i stylu liczby.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

Liczba zmiennoprzecinkowa o pojedynczej precyzji równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określoną zapakowaną wartość na liczbę zmiennoprzecinkową o pojedynczej precyzji.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Współdzielony wskaźnik do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

Liczba zmiennoprzecinkowa o pojedynczej precyzji równoważna podanej opakowanej wartości

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasa [Object](../../object/)
* Struktura [Convert](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)