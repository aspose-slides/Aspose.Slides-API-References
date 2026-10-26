---
title: Write()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zapisuje określony znak do strumienia.
type: docs
weight: 79
url: /pl/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metoda

Zapisuje określony znak do strumienia.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Znak do zapisania |

## StreamWriter::Write(const String\&) metoda

Zapisuje określony ciąg znaków do strumienia.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Ciąg znaków do zapisania |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metoda

Zapisuje reprezentację tekstową określonego obiektu do strumienia.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt do zapisania |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metoda

Zapisuje wszystkie znaki z określonej tablicy do strumienia.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres znaków UTF-16 z określonej tablicy znaków do strumienia.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |
| index | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba znaków w podzakresie do zapisania; -1 oznacza, że podzakres kończy się tam, gdzie kończy się tablica **buffer** |

## StreamWriter::Write(const char_t *) metoda

Zapisuje określony ciąg znaków typu C do strumienia.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const char_t * | Ciąg znaków typu C do zapisania |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metoda

Zapisuje reprezentację tekstową określonego obiektu do strumienia.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ obiektu |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Obiekt do zapisania |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [StreamWriter](../)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)