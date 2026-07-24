---
title: Build()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Objekt mit direktem Besitz.
type: docs
weight: 2289
url: /de/system/build/
---
## System::Build(Args\&&...) Funktion

Erstellt ein Objekt mit direktem Besitz.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des zu erstellenden Objekts |
| Args | Argumenttypen für die Objekterstellung |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | Args\&&... | Argumente, die an den Objektkonstruktor weitergeleitet werden |

### Rückgabewert

ObjectBuilder konfiguriert für direkte Objekterstellung

## Bemerkungen

[Object](../object/) Konstruktion muss mit dem Aufruf von [Get()](../get/) abgeschlossen werden

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)