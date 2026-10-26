---
title: EndRead()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a operação de leitura assíncrona especificada seja concluída.
type: docs
weight: 261
url: /pt/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) método


Aguarda até que a operação de leitura assíncrona especificada seja concluída.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação de leitura assíncrona |

### Valor de Retorno

O número de bytes lidos durante a operação de leitura representada por **asyncResult**

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IAsyncResult](../../../system/iasyncresult/)
* classe [NetworkStream](../)
* namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)