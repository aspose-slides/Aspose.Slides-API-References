---
title: WriteState
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa stan XmlWriter.
type: docs
weight: 755
url: /pl/system.xml/writestate/
---
## WriteState enum

Określa stan [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Start | 0 | Wskazuje, że metoda XmlWriter::Write nie została jeszcze wywołana. |
| Prolog | 1 | Wskazuje, że prolog jest zapisywany. |
| Element | 2 | Wskazuje, że tag początkowy elementu jest zapisywany. |
| Attribute | 3 | Wskazuje, że wartość atrybutu jest zapisywana. |
| Content | 4 | Wskazuje, że zawartość elementu jest zapisywana. |
| Closed | 5 | Wskazuje, że metoda [XmlWriter::Close](../xmlwriter/close/) została wywołana. |
| Error | 6 | Wystąpił wyjątek, który pozostawił [XmlWriter](../xmlwriter/) w nieprawidłowym stanie. Możesz wywołać metodę [XmlWriter::Close](../xmlwriter/close/), aby umieścić [XmlWriter](../xmlwriter/) w stanie [WriteState::Closed](./). Jakiekolwiek inne wywołania metod [XmlWriter](../xmlwriter/) skutkują InvalidOperationException. |

## Zobacz także

* Przestrzeń nazw [System::Xml](../)
* Biblioteka [Aspose.Slides](../../)