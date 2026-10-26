---
title: EndRead()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a operação de leitura assíncrona especificada seja concluída.
type: docs
weight: 430
url: /pt/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) método

Aguarda até que a operação de leitura assíncrona especificada seja concluída.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação de leitura assíncrona |

### Valor de Retorno

O número de bytes lidos durante a operação de leitura representada por **asyncResult**

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)