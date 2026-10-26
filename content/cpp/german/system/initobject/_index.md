---
title: InitObject()
second_title: Aspose.Slides für C++ API Referenz
description: Startet die Initialisierung eines Objekts mit gemeinsamer Besitzerschaft.
type: docs
weight: 2263
url: /de/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) Funktion

Starts initialization of an object with shared ownership.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Typ des zu initialisierenden Objekts |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) zum Initialisieren |

## Rückgabewert

ObjectBuilder konfiguriert für die Konstruktion von Shared-Pointern

## Bemerkungen

[Object](../object/) Initialisierung muss mit dem Aufruf von [Get()](../get/) beendet werden

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)