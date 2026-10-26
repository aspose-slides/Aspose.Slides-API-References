---
title: ToSByte()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje podaną wartość logiczną na równoważną 8-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 105
url: /pl/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metoda

Konwertuje podaną wartość logiczną na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```
## Convert::ToSByte(uint8_t) metoda

Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```
## Convert::ToSByte(int8_t) metoda

Zwraca podaną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```
## Convert::ToSByte(uint16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```
## Convert::ToSByte(int16_t) metoda

Konwertuje podaną 16-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```
## Convert::ToSByte(uint32_t) metoda

Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```
## Convert::ToSByte(int32_t) metoda

Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```
## Convert::ToSByte(uint64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```
## Convert::ToSByte(int64_t) metoda

Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```
## Convert::ToSByte(float) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu float na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(float value)
```
## Convert::ToSByte(double) metoda

Konwertuje podaną liczbę zmiennoprzecinkową typu double na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(double value)
```
## Convert::ToSByte(const Decimal\&) metoda

Konwertuje podaną liczbę dziesiętną na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```
## Convert::ToSByte(char_t) metoda

Konwertuje podany znak Unicode na równoważną 8-bitową liczbę całkowitą ze znakiem.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```
## Convert::ToSByte(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```
## Convert::ToSByte(std::nullptr_t) metoda

Konwertuje podany null-string na równoważną 8-bitową wartość całkowitą.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Wartość zwracana

Zero.

## Convert::ToSByte(const char_t *) metoda

Konwertuje podany c-string zawierający tekstową reprezentację liczby na równoważną 8-bitową wartość całkowitą.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji |

### Wartość zwracana

8-bitowa wartość całkowita równa liczbie reprezentowanej przez podany c-string

## Convert::ToSByte(const String\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową wartość całkowitą.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

8-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSByte(const String\&, int) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby w określonej podstawie na równoważną 8-bitową wartość całkowitą.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| from_base | int | Podstawa liczby reprezentowanej przez ciąg znaków |

### Wartość zwracana

8-bitowa wartość całkowita równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową liczbę całkowitą bez znaku przy użyciu dostarczonych informacji o formatowaniu.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków zawierający tekstową reprezentację liczby na równoważną 8-bitową wartość całkowitą przy użyciu dostarczonych informacji o formatowaniu i stylu liczby.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolony styl tekstowej reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik na obiekt zawierający informacje o formacie ciągu znaków |

### Wartość zwracana

8-bitowa liczba całkowita bez znaku równa liczbie reprezentowanej przez podany ciąg znaków

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metoda

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podaną wartość opakowaną na równoważną 8-bitową wartość całkowitą.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wspólny wskaźnik do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

8-bitowa wartość całkowita równoważna podanej wartości opakowanej

## Zobacz także

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)