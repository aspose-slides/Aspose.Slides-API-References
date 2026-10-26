---
title: BeginRead()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação de leitura assíncrona.
type: docs
weight: 417
url: /pt/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método

Inicia uma operação de leitura assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes de onde ler os dados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| count | **int32_t** | O número de bytes a ler. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Uma função de retorno de chamada a ser invocada quando a operação for concluída. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação de leitura assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de leitura assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)