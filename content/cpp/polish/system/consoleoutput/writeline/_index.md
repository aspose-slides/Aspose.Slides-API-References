---
title: WriteLine()
second_title: Aspose.Slides dla C++ - referencja API
description: Zapisuje bieżący znak końca linii do strumienia wyjściowego reprezentowanego przez bieżący obiekt.
type: docs
weight: 27
url: /pl/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() metoda

Zapisuje bieżący znacznik końca linii do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) metoda

Zapisuje łańcuchową reprezentację określonego obiektu, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Obiekt do wyjścia |

## ConsoleOutput::WriteLine(bool) metoda

Zapisuje łańcuchową reprezentację określonej wartości bool, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **bool** | Obiekt do wyjścia |

## ConsoleOutput::WriteLine(char_t) metoda

Zapisuje określoną wartość znaku, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Wartość do wyjścia |

## ConsoleOutput::WriteLine(Decimal) metoda

Zapisuje łańcuchową reprezentację wartości [Decimal](../../decimal/), a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | Wartość do wyjścia |

## ConsoleOutput::WriteLine(double) metoda

Zapisuje łańcuchową reprezentację wartości zmiennoprzecinkowej podwójnej precyzji, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **double** | Wartość do wyjścia |

## ConsoleOutput::WriteLine(int) metoda

Zapisuje łańcuchową reprezentację 32-bitowej wartości całkowitej, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int | Wartość do wyjścia |

## ConsoleOutput::WriteLine(int64_t) metoda

Zapisuje łańcuchową reprezentację 64-bitowej wartości całkowitej, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int64_t** | Wartość do wyjścia |

## ConsoleOutput::WriteLine(float) metoda

Zapisuje łańcuchową reprezentację wartości zmiennoprzecinkowej pojedynczej precyzji, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **float** | Wartość do wyjścia |

## ConsoleOutput::WriteLine(const String\&) metoda

Zapisuje określony obiekt łańcucha znaków, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Obiekt łańcucha do wyjścia |

## ConsoleOutput::WriteLine(uint32_t) metoda

Zapisuje łańcuchową reprezentację 32-bitowej liczby całkowitej bez znaku, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint32_t** | Wartość do wyjścia |

## ConsoleOutput::WriteLine(uint64_t) metoda

Zapisuje łańcuchową reprezentację 64-bitowej liczby całkowitej bez znaku, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **uint64_t** | Wartość do wyjścia |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) metoda

Zapisuje łańcuchową reprezentację określonej tablicy znaków, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Tablica do wyjścia |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje łańcuchową reprezentację zakresu wartości określonej tablicy znaków, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Tablica zawierająca wartości do wyjścia |
| index | **int32_t** | Indeks, od którego zaczyna się zakres elementów do wyjścia |
| count | **int32_t** | Liczba elementów w zakresie elementów do wyjścia |

## ConsoleOutput::WriteLine(const char_t *) metoda

Zapisuje określony ciąg znaków C, a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | Ciąg znaków C do wyjścia |

## ConsoleOutput::WriteLine(const TypeInfo\&) metoda

Zapisuje łańcuchową reprezentację określonego obiektu [TypeInfo](../../typeinfo/), a następnie bieżący znacznik końca linii, do strumienia wyjściowego reprezentowanego przez bieżący obiekt.

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Obiekt [TypeInfo](../../typeinfo/) do wyjścia |

## ConsoleOutput::WriteLine(const char *) metoda

```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)