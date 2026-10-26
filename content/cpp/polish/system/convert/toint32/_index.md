---
title: ToInt32()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje określoną wartość logiczną na równoważną 32-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 157
url: /pl/system/convert/toint32/
---
## Convert::ToInt32(bool) metoda

Konwertuje podaną wartość logiczną na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) metoda

Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) metoda

Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) metoda

Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) metoda

Zwraca podaną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu float na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu double na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) metoda

Konwertuje podaną liczbę dziesiętną na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) metoda

Konwertuje podany znak Unicode na równoważną 32-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) metoda

Konwertuje podany null-string na równoważną 32-bitową wartość całkowitą.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Wartość zwracana

Zero.

## Convert::ToInt32(const char_t *) metoda

Konwertuje określony c-string zawierający tekstową reprezentację liczby na równoważną 32-bitową wartość całkowitą.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | c-string do konwersji |

### Wartość zwracana

32-bitowa wartość całkowita równa liczbie reprezentowanej przez podany c-string

## Convert::ToInt32(const String\&) metoda

Konwertuje określony ciąg znaków zawierający tekstową reprezentację liczby na równoważną 32-bitową wartość całkowitą.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | ciąg znaków do konwersji |

### Wartość zwracana

32-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToInt32(const String\&, int) metoda

Konwertuje określony ciąg znaków zawierający tekstową reprezentację liczby w podanej podstawie na równoważną 32-bitową wartość całkowitą.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | ciąg znaków do konwersji |
| from_base | int | Podstawa liczby reprezentowanej przez ciąg znaków |

### Wartość zwracana

32-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony ciąg znaków zawierający tekstową reprezentację liczby na równoważną 32-bitową wartość całkowitą przy użyciu podanych informacji o formatowaniu.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

32-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) metoda

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony ciąg znaków zawierający tekstową reprezentację liczby na równoważną 32-bitową wartość całkowitą przy użyciu podanych informacji o formatowaniu i stylu liczby.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl tekstowej reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

32-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metoda

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podaną wartość opakowaną na równoważną 32-bitową wartość całkowitą.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format łańcucha znaków używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

32-bitowa wartość całkowita równoważna podanej opakowanej wartości

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
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)