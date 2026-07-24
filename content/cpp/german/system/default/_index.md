---
title: Default()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Referenz auf die einzelne standardkonstruierten Instanz des Ausnahmetyps zurück.
type: docs
weight: 2224
url: /de/system/default/
---
## System::Default() Funktion

Gibt die Referenz auf die einzelne standardkonstruierten Instanz des Ausnahmetyps zurück.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ, dessen Instanz zurückgegeben wird |

## System::Default() Funktion

Gibt die Referenz auf die einzelne standardkonstruierten Instanz des Nicht-Ausnahmetyps zurück.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ, dessen Instanz zurückgegeben wird |

## Siehe auch

* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)