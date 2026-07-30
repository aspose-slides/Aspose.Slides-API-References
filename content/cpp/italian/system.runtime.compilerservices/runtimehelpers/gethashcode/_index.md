---
title: GetHashCode()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene il codice hash su un tipo arbitrario. Chiama Object::GetHashCode() per farlo."
type: docs
weight: 1
url: /it/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) metodo


Ottiene il codice hash su un tipo arbitrario. Chiama [Object::GetHashCode()](../../../system/object/gethashcode/) per farlo.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


### Parametri del modello

| Parameter | Description |
| --- | --- |
| T | Tipo per cui ottenere il codice hash. |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) da cui ottenere le informazioni. |

### Valore restituito

Valore del codice hash calcolato dall'implementazione di destinazione.

## Vedi anche

* Classe [SmartPtr](../../../system/smartptr/)
* Classe [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Libreria [Aspose.Slides](../../../)