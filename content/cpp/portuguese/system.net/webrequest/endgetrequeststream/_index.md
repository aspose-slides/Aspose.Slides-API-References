---
title: EndGetRequestStream()
second_title: Aspose.Slides para C++ Referência da API
description: Aguarda até que a operação assíncrona especificada para obter um stream seja concluída.
type: docs
weight: 313
url: /pt/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) method

Aguarda até que a operação assíncrona especificada para obter um fluxo seja concluída.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação assíncrona para obter um stream. |

### Valor de Retorno

O fluxo para gravar dados no recurso.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)