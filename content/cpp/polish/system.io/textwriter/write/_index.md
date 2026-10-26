---
title: Write()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zapisuje reprezentację tekstową określonego obiektu do strumienia.
type: docs
weight: 105
url: /pl/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metoda

Zapisuje reprezentację tekstową określonego obiektu do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt do zapisania |

## TextWriter::Write(bool) metoda

Zapisuje reprezentację tekstową określonej wartości logicznej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **bool** | Wartość do zapisania |

## TextWriter::Write(char_t) metoda

Zapisuje określony znak do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Wartość do zapisania |

## TextWriter::Write(Decimal) metoda

Zapisuje reprezentację tekstową określonego [Decimal](../../../system/decimal/) obiektu do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Obiekt do zapisania |

## TextWriter::Write(double) metoda

Zapisuje reprezentację tekstową określonej podwójnej precyzji liczby zmiennoprzecinkowej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do zapisania |

## TextWriter::Write(int) metoda

Zapisuje reprezentację tekstową określonej 32-bitowej liczby całkowitej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int | Wartość do zapisania |

## TextWriter::Write(int64_t) metoda

Zapisuje reprezentację tekstową określonej 64-bitowej liczby całkowitej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int64_t** | Wartość do zapisania |

## TextWriter::Write(float) metoda

Zapisuje reprezentację tekstową określonej pojedynczej precyzji liczby zmiennoprzecinkowej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zapisania |

## TextWriter::Write(const String\&) metoda

Zapisuje określony ciąg znaków do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Ciąg znaków do zapisania |

## TextWriter::Write(uint32_t) metoda

Zapisuje reprezentację tekstową określonej nieujemnej 32-bitowej liczby całkowitej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint32_t** | Wartość do zapisania |

## TextWriter::Write(uint64_t) metoda

Zapisuje reprezentację tekstową określonej nieujemnej 64-bitowej liczby całkowitej do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint64_t** | Wartość do zapisania |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metoda

Zapisuje wszystkie znaki z określonej tablicy do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres znaków UTF-16 z określonej tablicy znaków do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |
| index | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba znaków w podzakresie do zapisania; -1 określa, że podzakres kończy się tam, gdzie kończy się tablica **buffer** |

## TextWriter::Write(const char_t *) metoda

Zapisuje określony ciąg C-string do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | Ciąg C-string do zapisania |

## TextWriter::Write(const TypeInfo\&) metoda

Zapisuje reprezentację tekstową określonego [TypeInfo](../../../system/typeinfo/) obiektu do strumienia.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Obiekt do zapisania |

## TextWriter::Write(const String\&, const TArgs\&...) metoda

Zapisuje określone wartości sformatowane zgodnie z podanym formatem do strumienia.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TArgs | Lista typów wartości do zapisania |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Format ciągu |
| args | const TArgs\&... | Wartości do zapisania |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TextWriter](../)
* Klasa [Decimal](../../../system/decimal/)
* Klasa [String](../../../system/string/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)