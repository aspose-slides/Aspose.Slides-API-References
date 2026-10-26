---
title: get_InterruptionToken()
second_title: Referência da API Aspose.Slides para C++
description: O token para monitorar solicitações de interrupção.
type: docs
weight: 235
url: /pt/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() método

O token para monitorar solicitações de interrupção.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Observações

Este token gerencia todo o tempo de vida da instância [IPresentation](../../ipresentation/). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) do [InterruptionTokenSource](../../interruptiontokensource/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)