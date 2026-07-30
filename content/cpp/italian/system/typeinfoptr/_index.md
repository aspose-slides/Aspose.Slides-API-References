---
title: TypeInfoPtr
second_title: Riferimento API di Aspose.Slides per C++
description: "Contenitore per un puntatore a un'istanza della classe TypeInfo. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1951
url: /it/system/typeinfoptr/
---
## TypeInfoPtr struct

Contenitore per un puntatore a un'istanza della classe [TypeInfo](../typeinfo/). Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class TypeInfoPtr
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | Restituisce un puntatore grezzo all'oggetto [TypeInfo](../typeinfo/) rappresentato. |
|  [TypeInfoPtr](./typeinfoptr/)() | Costruttore predefinito. |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | Costruttore. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | Costruttore. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | Costruttore. |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | Costruttore. |
|  [~TypeInfoPtr](./~typeinfoptr/)() | Distruttore. |
## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)