---
title: SmartPtrInfo
second_title: Riferimento API di Aspose.Slides per C++
description: Classe di servizio per testare e modificare il contenuto di SmartPtr senza conoscere il tipo finale. Utilizzata per la raccolta dei rifiuti e il rilevamento di riferimenti ciclici, ecc. Pensala come un 'pointer to pointer'. Non possiamo usare il tipo base di SmartPtr poiché non ne ha uno; invece, utilizziamo questa classe 'info'.
type: docs
weight: 1249
url: /it/system/smartptrinfo/
---
## SmartPtrInfo classe

Classe di servizio per testare e modificare il contenuto di [SmartPtr](../smartptr/) senza conoscere il tipo finale. Utilizzata per la raccolta dei rifiuti e il rilevamento di riferimenti a ciclo, ecc. Pensala come un 'pointer to pointer'. Non possiamo usare il tipo base di [SmartPtr](../smartptr/) poiché non ne ha uno; invece, utilizziamo questa classe 'info'.

```cpp
class SmartPtrInfo
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Ottiene l'oggetto grezzo a cui punta il puntatore di riferimento. |
| [Object](../object/) * [getObject](./getobject/)() const | Ottiene l'oggetto a cui punta il puntatore di riferimento. |
| [Object](../object/) * [getOwned](./getowned/)() const | Ottiene il puntatore posseduto dall'oggetto. |
| [operator bool](./operator_bool/)() const | Verifica se l'oggetto info punta a un puntatore non null. |
| **bool** [operator!](./operator_not/)() const | Verifica se l'oggetto info non punta a un puntatore non null. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Consente di chiamare i metodi di [Object](../object/) a cui punta il puntatore di riferimento. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Confronta con minore i valori dei puntatori referenziati da due oggetti info. |
| [SmartPtrInfo](./smartptrinfo/)() | Crea un oggetto [SmartPtrInfo](./) vuoto. |
| explicit [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Crea un oggetto [SmartPtrInfo](./) con informazioni su uno smart pointer specifico. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)