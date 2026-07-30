---
title: get_InterruptionToken()
second_title: Riferimento API di Aspose.Slides per C++
description: Il token per monitorare le richieste di interruzione.
type: docs
weight: 235
url: /it/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() metodo

Il token per monitorare le richieste di interruzione.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Osservazioni

Questo token gestisce l'intera durata dell'istanza [IPresentation](../../ipresentation/). Qualsiasi operazione a lungo termine, come il caricamento o il salvataggio della presentazione, verrà interrotta chiamando il metodo [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) dell'[InterruptionTokenSource](../../interruptiontokensource/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)