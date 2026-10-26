---
title: get_PortionFormat()
second_title: Riferimento API di Aspose.Slides per C++ 
description: Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata. Solo lettura IPortionFormat.
type: docs
weight: 1
url: /it/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metodo

Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata. Solo lettura [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Osservazioni

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per la porzione corrente, i dati ereditati non sono applicati.

Per ottenere i valori effettivi inclusi quelli ereditati, utilizzare il metodo [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../iportionformat/)
* Classe [Portion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)