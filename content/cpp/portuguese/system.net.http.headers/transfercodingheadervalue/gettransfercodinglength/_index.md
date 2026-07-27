---
title: GetTransferCodingLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string passada do índice especificado para uma instância da classe TransferCodingHeaderValue.
type: docs
weight: 105
url: /pt/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) method

Converte uma string passada do índice especificado para uma instância da classe [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Uma instância onde um objeto analisado será atribuído. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | O delegate que é usado para criar instâncias da classe [TransferCodingHeaderValue](../). |

### Valor de Retorno

Retorna o comprimento de uma substring analisada, caso contrário 0.

## Veja Também

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)