---
title: BuildObject()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Objekt mit gemeinsamem Besitz.
type: docs
weight: 2250
url: /de/system/buildobject/
---
## System::BuildObject(Args\&&...) Funktion

Erstellt ein Objekt mit gemeinsamem Besitz.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
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

ObjectBuilder konfiguriert für die SharedPtr-Konstruktion

## Hinweise

Erstellt einen SharedPtr<T> und gibt einen Builder dafür zurück
[Object](../object/) Konstruktion muss mit dem Aufruf von [Get()](../get/) abgeschlossen werden

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)