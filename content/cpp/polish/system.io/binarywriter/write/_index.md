---
title: Write()
second_title: Referencja API Aspose.Slides dla C++
description: Zapisuje podaną nieoznaczoną 8-bitową wartość całkowitą do strumienia wyjściowego.
type: docs
weight: 92
url: /pl/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metoda

Zapisuje podaną nieoznaczoną 8-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint8_t** | Wartość do zapisania |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metoda

Zapisuje podany podzakres bajtów z określonej tablicy bajtów do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania |
| index | int | Indeks zerowy elementu w **buffer**, od którego rozpoczyna się podzakres do zapisania |
| count | int | Liczba elementów w podzakresie do zapisania; -1 oznacza, że podzakres kończy się tam, gdzie kończy się tablica **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metoda

Zapisuje podany podzakres znaków UTF-16 z określonej tablicy znaków do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |
| index | int | Indeks zerowy elementu w **buffer**, od którego rozpoczyna się podzakres do zapisania |
| count | int | Liczba znaków w podzakresie do zapisania; -1 oznacza, że podzakres kończy się tam, gdzie kończy się tablica **buffer** |

## BinaryWriter::Write(bool) metoda

Zapisuje pojedynczy bajt o wartości 0, jeśli **value** jest 'true', oraz 1, jeśli **value** jest 'false', do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **bool** | Wartość logiczna określająca wartość bajtu do zapisania w strumieniu wyjściowym |

## BinaryWriter::Write(char16_t) metoda

Zapisuje podaną 16-bitową wartość znaku do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char16_t | Wartość do zapisania |

## BinaryWriter::Write(int16_t) metoda

Zapisuje podaną 16-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int16_t** | Wartość do zapisania |

## BinaryWriter::Write(int) metoda

Zapisuje podaną 32-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int | Wartość do zapisania |

## BinaryWriter::Write(int64_t) metoda

Zapisuje podaną 64-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int64_t** | Wartość do zapisania |

## BinaryWriter::Write(uint16_t) metoda

Zapisuje podaną nieoznaczoną 16-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint16_t** | Wartość do zapisania |

## BinaryWriter::Write(uint32_t) metoda

Zapisuje podaną nieoznaczoną 32-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint32_t** | Wartość do zapisania |

## BinaryWriter::Write(uint64_t) metoda

Zapisuje podaną nieoznaczoną 64-bitową wartość całkowitą do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint64_t** | Wartość do zapisania |

## BinaryWriter::Write(float) metoda

Zapisuje podaną wartość zmiennoprzecinkową pojedynczej precyzji do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do zapisania |

## BinaryWriter::Write(double) metoda

Zapisuje podaną wartość zmiennoprzecinkową podwójnej precyzji do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do zapisania |

## BinaryWriter::Write(const Decimal\&) metoda

Zapisuje bajtową reprezentację podanej wartości [Decimal](../../../system/decimal/) do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Wartość do zapisania |

## BinaryWriter::Write(const String\&) metoda

Zapisuje łańcuch z prefiksem długości w bieżącym kodowaniu do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Łańcuch do zapisania |

## BinaryWriter::Write(const char_t *) metoda

Zapisuje łańcuch z prefiksem długości w bieżącym kodowaniu do strumienia wyjściowego.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do zapisania |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [BinaryWriter](../)
* Klasa [Decimal](../../../system/decimal/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)