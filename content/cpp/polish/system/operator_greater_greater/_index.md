---
title: operator>>()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Pobiera łańcuch znaków ze strumienia wejściowego, używając kodowania UTF-8.
type: docs
weight: 3004
url: /pl/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) funkcja

Pobiera łańcuch znaków z strumienia wejściowego przy użyciu kodowania UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in | std::istream\& | Obiekt strumienia wejściowego (instancja **basic_ostream** z **char**). |
| str | [String](../string/)\& | Łańcuch znaków do odczytania ze strumienia wejściowego. |

### Wartość zwracana

Strumień wejściowy, z którego wyodrębniono łańcuch znaków.

## System::operator>>(std::wistream\&, String\&) funkcja

Pobiera łańcuch znaków ze strumienia wejściowego.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| in | std::wistream\& | Obiekt strumienia wejściowego (instancja **basic_ostream** z ****wchar_t****). |
| str | [String](../string/)\& | Łańcuch znaków do odczytania ze strumienia wejściowego. |

### Wartość zwracana

Strumień wejściowy, z którego wyodrębniono łańcuch znaków.

## Zobacz także

* Klasa [String](../string/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)