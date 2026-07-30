---
title: "System::Collections"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 300
url: /it/system.collections/
---
## Classi

| Class | Description |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) di bit che possono essere indirizzati per indice. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché causerà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza tale puntatore per passarla alle funzioni come argomento. |
| [BitArrayPtr](./bitarrayptr/) | Puntatore a [BitArray](./bitarray/). Questo tipo è un puntatore per gestire la cancellazione di altri oggetti. Dovrebbe essere allocato sullo stack e passato alle funzioni sia per valore sia per riferimento costante. |
| [CollectionBase](./collectionbase/) | Fornisce una classe base astratta per una collezione fortemente tipizzata. |
| [ICollection](./icollection/) | Definisce un'interfaccia di collezione non generica. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) è l'interfaccia base per tutte le collezioni non generiche che possono essere enumerate. |
| [IEnumerator](./ienumerator/) | Interfaccia di enumeratore che può essere usata per iterare attraverso alcuni elementi. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché causerà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e utilizza tale puntatore per passarla alle funzioni come argomento. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper che crea un'implementazione non generica [IEnumerator](./ienumerator/) sopra l'Iterator generico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper per i tipi di riferimento. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper che crea un'implementazione non generica [IEnumerator](./ienumerator/) sopra l'Iterator generico [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper per i tipi valore. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Rappresenta una collezione non generica di oggetti che possono essere acceduti individualmente per indice. |
| [IListImplRefType](./ilistimplreftype/) | Stub che implementa l'interfaccia [System::Collections::IList](./ilist/) su un oggetto [System::Collections::Generic::List](../system.collections.generic/list/). Implementazione per i tipi di riferimento. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub che implementa l'interfaccia [System::Collections::IList](./ilist/) su un oggetto [System::Collections::Generic::List](../system.collections.generic/list/). Implementazione per i tipi valore. |
| [IListWrapper](./ilistwrapper/) | Interfaccia per supportare il casting da collezione generica a non generica. |
| [Invalidatable](./invalidatable/) | Classe che rende possibile tracciare lo stato dei suoi discendenti tramite oggetti [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Classe che implementa i tracker degli oggetti [Invalidatable](./invalidatable/). |