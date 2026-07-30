---
title: set_InterruptionToken()
second_title: Riferimento API di Aspose.Slides per C++
description: Il token per monitorare le richieste di interruzione.
type: docs
weight: 248
url: /it/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metodo


Il token per monitorare le richieste di interruzione.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Osservazioni


Questo token gestisce l'intera durata dell'istanza [IPresentation](../../ipresentation/). Qualsiasi operazione a lungo termine, come il caricamento o il salvataggio della presentazione, verrà interrotta chiamando il metodo [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) del [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)