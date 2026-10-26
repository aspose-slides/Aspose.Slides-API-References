---
title: WriteState
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den Zustand des XmlWriter an.
type: docs
weight: 755
url: /de/system.xml/writestate/
---
## WriteState Enum

Gibt den Zustand von [XmlWriter](../xmlwriter/) an.

```cpp
enum class WriteState
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Start | 0 | Gibt an, dass die XmlWriter::Write-Methode noch nicht aufgerufen wurde. |
| Prolog | 1 | Gibt an, dass das Prolog geschrieben wird. |
| Element | 2 | Gibt an, dass ein Element-Start-Tag geschrieben wird. |
| Attribute | 3 | Gibt an, dass ein Attributwert geschrieben wird. |
| Content | 4 | Gibt an, dass Elementinhalt geschrieben wird. |
| Closed | 5 | Gibt an, dass die [XmlWriter::Close](../xmlwriter/close/)-Methode aufgerufen wurde. |
| Error | 6 | Es wurde eine Ausnahme ausgelöst, die [XmlWriter](../xmlwriter/) in einen ungültigen Zustand versetzt hat. Sie können die [XmlWriter::Close](../xmlwriter/close/)-Methode aufrufen, um [XmlWriter](../xmlwriter/) in den [WriteState::Closed](./)-Zustand zu versetzen. Jeder andere Aufruf einer [XmlWriter](../xmlwriter/)-Methode führt zu einer InvalidOperationException. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)