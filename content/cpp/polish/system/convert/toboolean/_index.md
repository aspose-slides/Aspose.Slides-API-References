---
title: ToBoolean()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca podaną wartość boolowską.
type: docs
weight: 79
url: /pl/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metoda

Zwraca podaną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metoda

Konwertuje podany 8-bitowy nieoznaczony całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metoda

Konwertuje podany 8-bitowy ze znakiem całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metoda

Konwertuje podany 16-bitowy nieoznaczony całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metoda

Konwertuje podany 16-bitowy ze znakiem całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metoda

Konwertuje podany 32-bitowy nieoznaczony całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metoda

Konwertuje podany 32-bitowy ze znakiem całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metoda

Konwertuje podany 64-bitowy nieoznaczony całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metoda

Konwertuje podany 64-bitowy ze znakiem całkowitą liczbę na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metoda

Konwertuje podaną liczbę typu float na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metoda

Konwertuje podaną liczbę typu double na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metoda

Konwertuje podaną liczbę dziesiętną na równoważną wartość boolowską.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metoda

Konwertuje podany null-string na równoważną wartość boolowską.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Wartość zwracana

False.

## Convert::ToBoolean(const char_t *) metoda

Konwertuje podany łańcuch znaków typu c na wartość typu bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-łańcuch znaków c do konwersji |

### Wartość zwracana

True jeśli podany c-łańcuch jest równy "True" i false jeśli podany c-łańcuch jest równy "False".

## Convert::ToBoolean(const String\&) metoda

Konwertuje podany ciąg znaków na wartość typu bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

True jeśli podany c-łańcuch jest równy "True" i false jeśli podany ciąg znaków jest równy "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podany ciąg znaków na wartość typu bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

True jeśli podany c-łańcuch jest równy "True" i false jeśli podany ciąg znaków jest równy "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje podaną opakowaną wartość na równoważną wartość boolowską.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format łańcucha znaków używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

Wartość boolowska równoważna podanej opakowanej wartości

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [Object](../../object/)
* Struktura [Convert](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)