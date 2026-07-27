---
title: get_InterruptionToken()
second_title: Aspose.Slides para C++ Referência da API
description: O token para monitorar solicitações de interrupção.
type: docs
weight: 235
url: /pt/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() método


O token para monitorar solicitações de interrupção.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Observações


O token gerencia todo o ciclo de vida da instância [IPresentation](../../ipresentation/). Qualquer operação de longa duração, como o carregamento ou a gravação de apresentação, será interrompida ao chamar o método [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) do [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)