---
title: ToInt64()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje podaną wartość logiczną na równoważną 64-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 183
url: /pl/system/convert/toint64/
---
## Convert::ToInt64(bool) metoda


Konwertuje podaną wartość logiczną na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metoda


Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metoda


Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metoda


Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metoda


Zwraca podaną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metoda


Konwertuje podaną liczbę zmiennoprzecinkową typu float na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metoda


Konwertuje podaną liczbę zmiennoprzecinkową typu double na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metoda


Konwertuje podaną liczbę dziesiętną na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metoda


Konwertuje podany znak Unicode na równoważną 64-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metoda


Konwertuje podany null-string na równoważną 64-bitową wartość całkowitą.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Wartość zwracana

Zero.

## Convert::ToInt64(const char_t *) metoda


Konwertuje podany c-string zawierający tekstową reprezentację liczby na równoważną 64-bitową wartość całkowitą.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji |

### Wartość zwracana

64-bitowa wartość całkowita równa liczbie przedstawionej w podanym c-stringu

## Convert::ToInt64(const String\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną 64-bitową wartość całkowitą.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | String do konwersji |

### Wartość zwracana

64-bitowa wartość całkowita równa liczbie przedstawionej w podanym stringu

## Convert::ToInt64(const String\&, int) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby w określonej podstawie na równoważną 64-bitową wartość całkowitą.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | String do konwersji |
| from_base | int | Podstawa systemu liczbowego reprezentacji liczby w stringu |

### Wartość zwracana

64-bitowa wartość całkowita równa liczbie przedstawionej w podanym stringu

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną 64-bitową wartość całkowitą przy użyciu podanych informacji o formatowaniu.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | String do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie stringu |

### Wartość zwracana

64-bitowa wartość całkowita równa liczbie przedstawionej w podanym stringu

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający tekstową reprezentację liczby na równoważną 64-bitową wartość całkowitą przy użyciu podanych informacji o formatowaniu i stylu liczby.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | String do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinacja bitowa wartości wyliczenia NumberStyles określająca dozwolony styl reprezentacji liczby w stringu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie stringu |

### Wartość zwracana

64-bitowa wartość całkowita równa liczbie przedstawionej w podanym stringu

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metoda




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podaną opakowaną wartość na równoważną 64-bitową wartość całkowitą.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format stringu używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

64-bitowa wartość całkowita równoważna podanej opakowanej wartości

## Zobacz także

* Wyliczenie [NumberStyles](../../../system.globalization/numberstyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasa [Object](../../object/)
* Struktura [Convert](../)
* Struktura [Enum](../../enum/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)