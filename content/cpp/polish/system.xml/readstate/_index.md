---
title: ReadState
second_title: Odwołanie API Aspose.Slides dla C++
description: Określa stan czytnika.
type: docs
weight: 703
url: /pl/system.xml/readstate/
---
## ReadState enum

Określa stan czytnika.

```cpp
enum class ReadState
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Initial | 0 | Metoda [XmlReader::Read](../xmlreader/read/) nie została wywołana. |
| Interactive | 1 | Metoda [XmlReader::Read](../xmlreader/read/) została wywołana. Dodatkowe metody mogą być wywoływane na czytniku. |
| Error | 2 | Wystąpił błąd, który uniemożliwia kontynuację operacji odczytu. |
| EndOfFile | 3 | Koniec pliku został pomyślnie osiągnięty. |
| Closed | 4 | Metoda [XmlReader::Close](../xmlreader/close/) została wywołana. |

## Zobacz także

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)