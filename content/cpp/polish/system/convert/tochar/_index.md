---
title: ToChar()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.
type: docs
weight: 118
url: /pl/system/convert/tochar/
---
## Convert::ToChar(bool) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metoda


Konwertuje podany 8-bitowy liczbowy typ bez znaku na równoważny znak unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metoda


Konwertuje podany 8-bitowy liczbowy typ ze znakiem na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metoda


Konwertuje podany 16-bitowy liczbowy typ bez znaku na równoważny znak unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metoda


Konwertuje podany 16-bitowy liczbowy typ ze znakiem na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metoda


Konwertuje podany 32-bitowy liczbowy typ bez znaku na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metoda


Konwertuje podany 32-bitowy liczbowy typ ze znakiem na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metoda


Konwertuje podany 64-bitowy liczbowy typ bez znaku na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metoda


Konwertuje podany 64-bitowy liczbowy typ ze znakiem na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metoda


Zwraca podany znak unicode.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metoda


Konwersja nie jest obsługiwana. Zawsze zgłasza InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metoda


Konwertuje pierwszy i jedyny znak podanego c-string na wartość char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji; oczekuje się, że c-string ma dokładnie 1 znak. |

### Wartość zwracana

Pierwszy i jedyny znak podanego c-string, jeśli ma dokładnie 1 znak, w przeciwnym razie - 0

## Convert::ToChar(const String\&) metoda


Konwertuje pierwszy i jedyny znak podanego ciągu znaków na wartość char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji; oczekuje się, że ciąg ma dokładnie 1 znak. |

### Wartość zwracana

Pierwszy i jedyny znak podanego ciągu znaków, jeśli ma dokładnie 1 znak, w przeciwnym razie - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje pierwszy i jedyny znak podanego ciągu znaków na wartość char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji; oczekuje się, że ciąg ma dokładnie 1 znak. |

### Wartość zwracana

Pierwszy i jedyny znak podanego ciągu znaków, jeśli ma dokładnie 1 znak, w przeciwnym razie - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Konwertuje podaną opakowaną wartość na równoważny znak unicode.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wskaźnik współdzielony do obiektu opakowującego wartość do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu znaków do użycia, jeśli typ opakowanej wartości jest [String](../../string/). |

### Wartość zwracana

Znak unicode równoważny podanej opakowanej wartości

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Decimal](../../decimal/)
* Klasa [DateTime](../../datetime/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [Object](../../object/)
* Struct [Convert](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)