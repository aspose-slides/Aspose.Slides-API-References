---
title: EndGetRequestStream()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a operação assíncrona especificada para obter um fluxo seja concluída.
type: docs
weight: 482
url: /pt/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a operação assíncrona especificada para obter um fluxo seja concluída.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação assíncrona para obter um fluxo. |

### Valor de Retorno

O fluxo para gravar dados no recurso.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [HttpWebRequest](../)
* Espaço de nomes [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)