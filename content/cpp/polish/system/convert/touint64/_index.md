---
title: ToUInt64()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Konwertuje określoną wartość logiczną na równoważną 64-bitową liczbę całkowitą bez znaku.
type: docs
weight: 196
url: /pl/system/convert/touint64/
---
## Convert::ToUInt64(bool) metoda


Konwertuje określoną wartość logiczną na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metoda


Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metoda


Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metoda


Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metoda


Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metoda


Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metoda


Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metoda


Zwraca określoną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metoda


Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metoda


Konwertuje określoną liczbę zmiennoprzecinkową typu float na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metoda


Konwertuje określoną liczbę zmiennoprzecinkową typu double na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metoda


Konwertuje określoną liczbę dziesiętną na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metoda


Konwertuje określony znak Unicode na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metoda


Konwertuje określony pusty ciąg znaków (null-string) na równoważną wartość 64-bitowej liczby całkowitej bez znaku.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Wartość zwracana

Zero.

## Convert::ToUInt64(const char_t *) metoda


Konwertuje określony ciąg znaków C (c-string) zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | Ciąg znaków C do konwersji |

### Wartość zwracana

Wartość 64-bitowej liczby całkowitej bez znaku równa liczbie przedstawionej w określonym ciągu znaków C

## Convert::ToUInt64(const String\&) metoda


Konwertuje określony łańcuch znaków zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch znaków do konwersji |

### Wartość zwracana

Wartość 64-bitowej liczby całkowitej bez znaku równa liczbie przedstawionej w określonym łańcuchu znaków

## Convert::ToUInt64(const String\&, int) metoda


Konwertuje określony łańcuch znaków zawierający tekstową reprezentację liczby w określonej podstawie na równoważną wartość 64-bitowej liczby całkowitej bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch znaków do konwersji |
| from_base | int | Podstawa liczby przedstawionej w łańcuchu znaków |

### Wartość zwracana

Wartość 64-bitowej liczby całkowitej bez znaku równa liczbie przedstawionej w określonym łańcuchu znaków

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określony łańcuch znaków zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku przy użyciu dostarczonych informacji o formatowaniu.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie łańcucha znaków |

### Wartość zwracana

Wartość 64-bitowej liczby całkowitej bez znaku równa liczbie przedstawionej w określonym łańcuchu znaków

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określony łańcuch znaków zawierający tekstową reprezentację liczby na równoważną wartość 64-bitowej liczby całkowitej bez znaku przy użyciu dostarczonych informacji o formatowaniu i stylu liczby.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Łańcuch znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl tekstowej reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie łańcucha znaków |

### Wartość zwracana

Wartość 64-bitowej liczby całkowitej bez znaku równa liczbie przedstawionej w określonym łańcuchu znaków

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metoda




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje określoną zapakowaną wartość na równoważną 64-bitową liczbę całkowitą bez znaku.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Współdzielony wskaźnik do obiektu, który opakowuje wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format łańcucha znaków, który będzie użyty, jeśli typ zapakowanej wartości jest [String](../../string/) |

### Wartość zwracana

64-bitowa liczba całkowita bez znaku równoważna określonej zapakowanej wartości

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
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