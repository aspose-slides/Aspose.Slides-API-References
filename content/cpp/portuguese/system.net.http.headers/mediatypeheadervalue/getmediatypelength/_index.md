---
title: GetMediaTypeLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string passada a partir do índice especificado para uma instância da classe MediaTypeHeaderValue.
type: docs
weight: 144
url: /pt/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) method


Converte uma string fornecida a partir do índice especificado para uma instância da [MediaTypeHeaderValue](../) class.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para a análise. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | O delegado usado para criar instâncias da [MediaTypeHeaderValue](../) class. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Uma instância onde um objeto analisado será atribuído. |

### Valor de Retorno

Retorna o comprimento de uma substring analisada, caso contrário 0.

## Veja Também

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)