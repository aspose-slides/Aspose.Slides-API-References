---
title: set_InterruptionToken()
second_title: Riferimento API di Aspose.Slides per C++
description: Il token da monitorare per le richieste di interruzione.
type: docs
weight: 248
url: /it/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) metodo


Il token da monitorare per richieste di interruzione.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Osservazioni


Questo token gestisce l'intera durata dell'istanza [IPresentation](../../ipresentation/). Qualsiasi operazione a lunga esecuzione, come il caricamento o il salvataggio di una presentazione, sarà interrotta chiamando il metodo [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) del [InterruptionTokenSource](../../interruptiontokensource/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)