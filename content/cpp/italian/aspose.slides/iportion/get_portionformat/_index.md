---
title: get_PortionFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata. Solo lettura IPortionFormat.
type: docs
weight: 1
url: /it/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() metodo

Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata. Solo lettura [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Osservazioni

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per la porzione corrente, i dati ereditati non vengono applicati.

Per ottenere i valori effettivi includendo quelli ereditati usa il metodo [IPortionFormat::GetEffective](../../iportionformat/geteffective/).
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../iportionformat/)
* Classe [IPortion](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)