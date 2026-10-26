---
title: WriteLine()
second_title: Aspose.Slides dla C++ – referencja API
description: Zapisuje znaki końca linii do strumienia.
type: docs
weight: 92
url: /pl/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metoda

Zapisuje znaki zakończenia linii do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metoda

Zapisuje podany ciąg znaków, po którym następują znaki zakończenia linii, do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Ciąg znaków do zapisania |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metoda

Zapisuje reprezentację tekstową podanego obiektu, po której następują znaki zakończenia linii, do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Obiekt do zapisania |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metoda

Zapisuje wszystkie znaki z podanej tablicy, po których następują znaki zakończenia linii, do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres znaków UTF-16 z podanej tablicy znaków, po którym następują znaki zakończenia linii, do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisania |
| index | **int32_t** | Indeks (liczony od zera) elementu w **buffer**, od którego zaczyna się podzakres do zapisania |
| count | **int32_t** | Liczba znaków w podzakresie do zapisania; -1 oznacza, że podzakres kończy się na końcu tablicy **buffer** |

## StreamWriter::WriteLine(const char_t *) metoda

Zapisuje podany ciąg znaków C, po którym następują znaki zakończenia linii, do strumienia.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const char_t * | Ciąg znaków C do zapisania |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metoda

Zapisuje reprezentację tekstową podanego obiektu, po której następują znaki zakończenia linii, do strumienia.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
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
* Biblioteka [Aspose.Slides](../../../)