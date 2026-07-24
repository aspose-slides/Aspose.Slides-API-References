---
title: BindingFlags
second_title: Aspose.Slides für C++ API Referenz
description: Definiert Modi für die Member- und Typensuche sowie Bindungen.
type: docs
weight: 157
url: /de/system.reflection/bindingflags/
---
## BindingFlags Enum


Definiert Modi für die Member- und Typensuche sowie Bindungen.

```cpp
enum class BindingFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | 0 | Keine besonderen Optionen. |
| IgnoreCase | 1 | Ignoriert die Groß-/Kleinschreibung des Namens bei der Suche nach dem Element. |
| DeclaredOnly | 2 | Sucht nur nach Membern, die im Typ deklariert sind, und nicht in Basistypen. |
| Instance | 4 | Durchsucht Instanzmember. |
| Static | 8 | Durchsucht statische Member. |
| Public | 16 | Durchsucht öffentliche Member. |
| NonPublic | 32 | Durchsucht nicht-öffentliche Member. |
| FlattenHierarchy | 64 | Durchsucht öffentliche und geschützte statische Member des Basistyps. |
| InvokeMethod | 256 | Ruft die Methode auf. |
| CreateInstance | 512 | Erstellt eine Instanz des reflektierten Typs. |
| GetField | 1024 | Liest den Feldwert. |
| SetField | 2048 | Setzt den Feldwert. |
| GetProperty | 4096 | Liest den Eigenschaftswert. |
| SetProperty | 8192 | Setzt den Eigenschaftswert. |
| PutDispProperty | 16384 | Setzt COM-Eigenschaft. |
| PutRefDispProperty | 32768 | Setzt COM-Referenzeigenschaft. |
| ExactBinding | 65536 | Der Typbindung muss exakt sein, ohne Typkonvertierungen. |
| SuppressChangeType | 131072 | Nicht unterstützt. |
| OptionalParamBinding | 262144 | Wählt die Überladung basierend auf der Anzahl der Argumente aus. |
| IgnoreReturn | 16777216 | Ignoriert den Rückgabewert der COM-Interop. |

## Siehe auch

* Namensraum [System::Reflection](../)
* Bibliothek [Aspose.Slides](../../)