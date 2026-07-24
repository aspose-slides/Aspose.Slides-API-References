---
title: WeakReference<>
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt weiterhin gelöscht werden kann.
type: docs
weight: 1522
url: /de/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> Klasse

Stellt eine schwache Referenz dar, die ein Objekt referenziert, während das Objekt weiterhin gelöscht werden kann.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Gibt an, ob das vom aktuellen WeakReference-Objekt referenzierte Objekt gelöscht wurde. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Gibt das vom aktuellen WeakReference-Objekt referenzierte Objekt (das Ziel) zurück. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Setzt das vom aktuellen WeakReference-Objekt referenzierte Objekt (das Ziel). |
|  [WeakReference](./weakreference/)() | Standardkonstruktor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor aus nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Initialisiert eine neue Instanz der WeakReference-Klasse, die das angegebene Objekt referenziert. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Initialisiert eine neue Instanz der WeakReference-Klasse, die das angegebene Objekt referenziert. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)