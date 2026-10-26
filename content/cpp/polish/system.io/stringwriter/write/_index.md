---
title: Write()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zapisuje określony znak do strumienia.
type: docs
weight: 40
url: /pl/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metoda

Zapisuje określony znak do strumienia.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char_t | Wartość do zapisu |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metoda

Zapisuje określony podzakres znaków z podanej tablicy znaków do strumienia.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Tablica zawierająca znaki do zapisu |
| index | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisu |
| count | **int32_t** | Liczba znaków w podzakresie do zapisu |

## StringWriter::Write(const String\&) metoda

Zapisuje określony ciąg znaków do strumienia.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Ciąg znaków do zapisu |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [StringWriter](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)