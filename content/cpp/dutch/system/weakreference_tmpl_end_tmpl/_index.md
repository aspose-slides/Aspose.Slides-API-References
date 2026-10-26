---
title: WeakReference<>
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een zwakke referentie voor, die naar een object verwijst terwijl dit object nog kan worden verwijderd.
type: docs
weight: 1522
url: /nl/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> klasse

Stelt een zwakke referentie voor, die naar een object verwijst terwijl dat object nog kan worden verwijderd.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Geeft een indicatie of het object waarnaar de huidige WeakReference verwijst is verwijderd. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Haalt het object (het doel) op waarnaar de huidige WeakReference verwijst. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Stelt het object (het doel) in waarnaar de huidige WeakReference verwijst. |
| [WeakReference](./weakreference/)() | Standaardconstructor. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Constructor vanuit nullptr. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Initialiseert een nieuw exemplaar van de WeakReference klasse, waarbij het opgegeven object wordt gerefereerd. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Initialiseert een nieuw exemplaar van de WeakReference klasse, waarbij het opgegeven object wordt gerefereerd. |
## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)