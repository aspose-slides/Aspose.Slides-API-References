---
title: Index
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un indice in una collezione. L'indice può essere dall'inizio o dalla fine. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1015
url: /it/system/index/
---
## classe Index

Rappresenta un indice in una collezione. L'indice può essere dall'inizio o dalla fine. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Determina se l'istanza corrente e il [Index](./) specificato rappresentano la stessa posizione. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Crea un [Index](./) relativo alla fine della collezione. |
| static constexpr [Index](./) [get_End](./get_end/)() | Ottiene un oggetto [Index](./) che rappresenta la fine di una collezione. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Ottiene un valore che indica se l'indice proviene dalla fine. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Ottiene un oggetto [Index](./) che rappresenta l'inizio di una collezione. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Ottiene il valore dell'indice. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'indice corrente. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Converte il [Index](./) corrente in un offset dall'inizio di una collezione con la lunghezza specificata. |
| constexpr [Index](./index/)() | Costruisce un'istanza che rappresenta l'inizio di una collezione. |
| constexpr [Index](./index/)(**int32_t**) | Costruisce un'istanza che rappresenta la posizione specificata dall'inizio di una collezione. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Costruisce un'istanza che rappresenta l'indice specificato. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)