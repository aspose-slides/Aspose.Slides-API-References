---
title: BeginWrite()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de escrita assíncrona.
type: docs
weight: 443
url: /pt/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de escrita assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes para gravar os dados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| count | **int32_t** | O número de bytes a gravar. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Uma função de retorno de chamada a ser chamada quando a operação for concluída. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar unicamente cada operação de escrita assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de escrita assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)