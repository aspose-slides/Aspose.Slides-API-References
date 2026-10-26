---
title: ToInt16()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje podaną wartość logiczną na równoważną 16-bitową liczbę całkowitą ze znakiem.
type: docs
weight: 131
url: /pl/system/convert/toint16/
---
## Convert::ToInt16(bool) metoda


Konwertuje podaną wartość logiczną na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) metoda


Konwertuje podaną 8-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) metoda


Konwertuje podaną 16-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) metoda


Zwraca podaną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) metoda


Konwertuje podaną 32-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) metoda


Konwertuje podaną 64-bitową liczbę całkowitą bez znaku na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) metoda


Konwertuje podaną 64-bitową liczbę całkowitą ze znakiem na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) metoda


Konwertuje podaną liczbę zmiennoprzecinkową typu float na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) metoda


Konwertuje podaną liczbę zmiennoprzecinkową typu double na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) metoda


Konwertuje podaną liczbę dziesiętną na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) metoda


Konwertuje podany znak Unicode na równoważną 16-bitową liczbę całkowitą ze znakiem.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza wyjątek InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) metoda


Konwertuje podany nullowy ciąg znaków na równoważną 16-bitową wartość całkowitą.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Wartość zwracana

Zero.

## Convert::ToInt16(const char_t *) metoda


Konwertuje podany c-string zawierający reprezentację liczbową na równoważną 16-bitową wartość całkowitą.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | c-string do konwersji |

### Wartość zwracana

16-bitowa wartość całkowita równa liczbie reprezentowanej przez podany c-string

## Convert::ToInt16(const String\&) metoda


Konwertuje podany string zawierający reprezentację liczbową na równoważną 16-bitową wartość całkowitą.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

16-bitowa wartość całkowita równa liczbie reprezentowanej przez podany string

## Convert::ToInt16(const String\&, int) metoda


Konwertuje podany string zawierający reprezentację liczbową w określonej podstawie na równoważną 16-bitową wartość całkowitą.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| from_base | int | Podstawa liczby reprezentowanej przez string |

### Wartość zwracana

16-bitowa wartość całkowita równa liczbie reprezentowanej przez podany string

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający reprezentację liczbową na równoważną 16-bitową wartość całkowitą przy użyciu dostarczonych informacji o formatowaniu.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków |

### Wartość zwracana

16-bitowa wartość całkowita równa liczbie reprezentowanej przez podany string

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podany string zawierający reprezentację liczbową na równoważną 16-bitową wartość całkowitą przy użyciu dostarczonych informacji o formatowaniu oraz stylu liczby.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dopuszczalny styl reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu znaków |

### Wartość zwracana

16-bitowa wartość całkowita równa liczbie reprezentowanej przez podany string

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metoda 




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podaną wartość opakowaną (boxed) na równoważną 16-bitową wartość całkowitą.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wspólny wskaźnik do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków używany, jeśli typ opakowanej wartości to [String](../../string/) |

### Wartość zwracana

16-bitowa wartość całkowita równoważna podanej wartości opakowanej

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