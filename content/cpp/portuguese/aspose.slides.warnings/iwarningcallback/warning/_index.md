---
title: Warning()
second_title: Referência da API Aspose.Slides para C++
description: Método de callback que recebe aviso e decide se a operação deve ser abortada.
type: docs
weight: 1
url: /pt/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) método


Método de callback que recebe aviso e decide se a operação deve ser abortada.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Aviso a ser processado. |

### Valor de Retorno

Decisão de abortamento [ReturnAction](../../returnaction/).

## Veja Também

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningInfo](../../iwarninginfo/)
* Class [IWarningCallback](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)