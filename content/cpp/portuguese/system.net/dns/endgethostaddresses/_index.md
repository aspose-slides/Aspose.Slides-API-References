---
title: EndGetHostAddresses()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a operação assíncrona especificada para criar uma nova instância IPHostEntry-class seja concluída.
type: docs
weight: 144
url: /pt/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) method


Aguarda até que a operação assíncrona especificada para criar uma nova instância IPHostEntry-class seja concluída.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação assíncrona. |

### Valor de Retorno

Uma nova instância IPHostEntry-class.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPAddress](../../ipaddress/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)