---
title: set_InterruptionToken()
second_title: Aspose.Slides para C++ Referência da API
description: O token para monitorar solicitações de interrupção.
type: docs
weight: 248
url: /pt/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken>) método

O token para monitorar solicitações de interrupção.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Observações

Este token gerencia todo o tempo de vida da instância [IPresentation](../../ipresentation/). Qualquer operação de longa duração, como carregamento ou salvamento de apresentação, será interrompida ao chamar o método [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) do [InterruptionTokenSource](../../interruptiontokensource/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)