---
title: set_InterruptionToken()
second_title: Referência da API Aspose.Slides para C++
description: O token para monitorar solicitações de interrupção.
type: docs
weight: 248
url: /pt/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) método

O token para monitorar solicitações de interrupção.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Observações

Este token gerencia todo o tempo de vida da instância [IPresentation](../../ipresentation/). Qualquer operação de longa duração, como o carregamento ou a gravação de apresentação, será interrompida ao chamar o método [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) do [IInterruptionTokenSource](../../iinterruptiontokensource/). 
## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)