---
title: ToDouble()
second_title: Aspose.Slides dla C++ – referencja API
description: Konwertuje podaną wartość logiczną na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.
type: docs
weight: 222
url: /pl/system/convert/todouble/
---
## Convert::ToDouble(bool) metoda


Konwertuje podaną wartość logiczną na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metoda


Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metoda


Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metoda


Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metoda


Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metoda


Konwertuje podaną liczbę pojedynczej precyzji na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metoda


Zwraca podaną liczbę typu double.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metoda


Konwertuje podaną liczbę dziesiętną na równoważną liczbę zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metoda


Konwersja nie jest obsługiwana. Zawsze rzuca wyjątek InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze rzuca wyjątek InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metoda


Konwertuje podany null-string na równoważną wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToDouble(const char_t *) metoda


Konwertuje podany c-string zawierający tekstową reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji |

### Return Value

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym c-stringu

## Convert::ToDouble(const String\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch do konwersji |

### Return Value

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym stringu

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji, używając podanych informacji o formatowaniu.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie łańcucha |

### Return Value

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym stringu

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metoda




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną wartość zmiennoprzecinkową podwójnej precyzji, używając podanych informacji o formatowaniu oraz stylu liczby.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie łańcucha |

### Return Value

Wartość zmiennoprzecinkowa podwójnej precyzji równa liczbie przedstawionej w podanym stringu

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podaną zarejestrowaną wartość na wartość zmiennoprzecinkową podwójnej precyzji. Jeśli typ zarejestrowanej wartości jest [String](../../string/), używany jest podany format łańcucha podczas konwersji.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony na obiekt opakowujący wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format łańcucha używany, jeśli typ zarejestrowanej wartości jest [String](../../string/) |

### Return Value

Wartość zmiennoprzecinkowa podwójnej precyzji równoważna podanej zarejestrowanej wartości

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)