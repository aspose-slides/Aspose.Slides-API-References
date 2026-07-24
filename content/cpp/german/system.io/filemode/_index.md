---
title: FileMode
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie eine Datei geöffnet werden soll.
type: docs
weight: 508
url: /de/system.io/filemode/
---
## FileMode enum


Gibt an, wie eine Datei geöffnet werden soll.

```cpp
enum class FileMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| CreateNew | 1 | Erstelle eine neue Datei. Wenn die Datei bereits existiert, wird eine Ausnahme ausgelöst. |
| Create | 2 | Erstelle eine neue Datei. Wenn die Datei bereits existiert, wird sie überschrieben. |
| Open | 3 | Öffne eine vorhandene Datei. Wenn die Datei nicht existiert, wird eine Ausnahme ausgelöst. |
| OpenOrCreate | 4 | Öffne eine vorhandene Datei oder erstelle eine neue, wenn sie nicht existiert. |
| Truncate | 5 | Öffne eine vorhandene Datei und kürze sie, sodass sie leer ist. Wenn die Datei nicht existiert, wird eine Ausnahme ausgelöst. |
| Append | 6 | Öffne eine vorhandene Datei und springe ans Ende oder erstelle eine neue, wenn sie nicht existiert. |

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)