---
title: operator<()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, czy bieżący obiekt reprezentuje wartość daty i czasu wcześniejszą niż wartość reprezentowana przez określony obiekt DateTimeOffset.
type: docs
weight: 560
url: /pl/system/datetimeoffset/operator_less/
---
## DateTimeOffset::operator<(const DateTimeOffset\&) const metoda

Określa, czy bieżący obiekt reprezentuje datę i godzinę wcześniejszą niż wartość reprezentowana przez określony [DateTimeOffset](../) obiekt.

```cpp
bool System::DateTimeOffset::operator<(const DateTimeOffset &other) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Obiekt [DateTimeOffset](../) używany do porównania bieżącego obiektu |

### Wartość zwracana

True jeśli wartość daty i godziny reprezentowana przez bieżący obiekt jest wcześniejsza niż wartość reprezentowana przez **other**, w przeciwnym razie - false

## DateTimeOffset::operator<(std::nullptr_t) const metoda

```cpp
constexpr bool System::DateTimeOffset::operator<(std::nullptr_t) const
```

## Zobacz także

* Klasa [DateTimeOffset](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)