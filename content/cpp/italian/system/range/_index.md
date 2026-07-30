---
title: Range
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un intervallo con un indice di inizio e di fine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 1197
url: /it/system/range/
---
## Classe Range

Rappresenta un intervallo con un indice di inizio e di fine. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai [System::SmartPtr](../smartptr/) classe per gestire oggetti di questo tipo.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Crea un intervallo che inizia all'inizio della raccolta e termina all'indice di fine specificato. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Determina se l'intervallo corrente è uguale all'intervallo specificato. |
| static constexpr [Range](./) [get_All](./get_all/)() | Restituisce un [Range](./) che rappresenta l'intera raccolta. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Ottiene l'indice End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Ottiene l'indice Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'intervallo corrente. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Calcola lo spostamento di inizio basato su zero e la lunghezza per la lunghezza della raccolta specificata. |
| constexpr [Range](./range/)() | Costruisce un intervallo vuoto. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Costruisce un [Range](./) dagli indici di inizio e fine specificati. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Crea un intervallo che inizia all'indice di inizio specificato e si estende fino alla fine della raccolta. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)