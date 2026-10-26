---
title: FileOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt erweiterte Optionen zum Erstellen eines FileStream-Objekts dar.
type: docs
weight: 521
url: /de/system.io/fileoptions/
---
## FileOptions Enum

Stellt erweiterte Optionen zum Erstellen eines [FileStream](../filestream/)-Objekts dar.

```cpp
enum class FileOptions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Keine zusätzlichen Optionen. |
| Encrypted | 16384 | Die Datei ist verschlüsselt. NOT IMPLEMENTED. |
| DeleteOnClose | 67108864 | Die Datei sollte automatisch gelöscht werden, wenn sie nicht mehr verwendet wird. |
| SequentialScan | 134217728 | Die Datei sollte sequenziell zugegriffen werden. |
| RandomAccess | 268435456 | Die Datei wird zufällig zugegriffen. |
| Asynchronous | 1073741824 | Die Datei kann für asynchrone I/O-Operationen verwendet werden. |
| WriteThrough | n/a | Alle Schreibvorgänge sollten direkt auf die Festplatte gehen und dabei jeglichen Zwischenspeicher umgehen. |

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)