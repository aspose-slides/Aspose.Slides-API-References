---
title: WeakReference<>
second_title: Aspose.Slides för C++ API-referens
description: Representerar en svag referens som refererar ett objekt samtidigt som det fortfarande tillåter att objektet tas bort.
type: docs
weight: 1522
url: /sv/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> klass

Representerar en svag referens som refererar ett objekt samtidigt som det fortfarande tillåter att objektet tas bort.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Hämtar en indikation på om objektet som refereras av det aktuella WeakReference objektet har tagits bort. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Hämtar objektet (målet) som refereras av det aktuella WeakReference objektet. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Sätter objektet (målet) som refereras av det aktuella WeakReference objektet. |
|  [WeakReference](./weakreference/)() | Standardkonstruktor. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Konstruktor från nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Initierar en ny instans av WeakReference klass som refererar det angivna objektet. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Initierar en ny instans av WeakReference klass som refererar det angivna objektet. |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)