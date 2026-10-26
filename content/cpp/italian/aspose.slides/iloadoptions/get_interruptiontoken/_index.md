---
title: get_InterruptionToken()
second_title: Riferimento API di Aspose.Slides per C++
description: Il token per monitorare le richieste di interruzione.
type: docs
weight: 235
url: /it/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() metodo


Il token per monitorare le richieste di interruzione.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Osservazioni


Questo token gestisce l'intera durata dell'istanza [IPresentation](../../ipresentation/). Qualsiasi operazione di lunga durata, come il caricamento o il salvataggio di una presentazione, verrà interrotta chiamando il metodo [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) del [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)