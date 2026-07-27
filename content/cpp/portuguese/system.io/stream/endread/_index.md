---
title: EndRead()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que a operação de leitura assíncrona especificada seja concluída.
type: docs
weight: 183
url: /pt/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) método

Espera até que a operação de leitura assíncrona especificada seja concluída.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa uma operação de leitura assíncrona |

### Valor de retorno

O número de bytes lidos durante a operação de leitura representada por **asyncResult**

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)