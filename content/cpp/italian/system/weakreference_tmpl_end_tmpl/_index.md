---
title: WeakReference<>
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un riferimento debole, che referenzia un oggetto consentendo comunque che l'oggetto venga eliminato.
type: docs
weight: 1522
url: /it/system/weakreference_tmpl_end_tmpl/
---
## classe WeakReference<>

Rappresenta un riferimento debole, che referenzia un oggetto consentendo allo stesso di essere cancellato.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Restituisce un’indicazione se l’oggetto referenziato dall’oggetto WeakReference corrente è stato eliminato. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Restituisce l’oggetto (il target) referenziato dall’oggetto WeakReference corrente. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Imposta l’oggetto (il target) referenziato dall’oggetto WeakReference corrente. |
|  [WeakReference](./weakreference/)() | Costruttore predefinito. |
|  [WeakReference](./weakreference/)(std::nullptr_t) | Costruttore da nullptr. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Inizializza una nuova istanza della classe WeakReference, referenziando l’oggetto specificato. |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Inizializza una nuova istanza della classe WeakReference, referenziando l’oggetto specificato. |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)