---
title: GetNameValueListLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string passada a partir do índice especificado para a coleção de instâncias da classe NameValueHeaderValue e retorna o comprimento de uma substring analisada.
type: docs
weight: 131
url: /pt/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) método

Converte uma string passada a partir do índice especificado para a coleção de instâncias da classe NameValueHeaderValue e retorna o comprimento de uma substring analisada.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string para analisar. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| delimiter | char16_t | Uma string usada para delimitar itens na string especificada. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | O parâmetro de saída onde será atribuída uma coleção analisada. |

### Valor de Retorno

O comprimento de uma substring analisada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ObjectCollection](../../objectcollection/)
* Classe [NameValueHeaderValue](../)
* Espaço de nomes [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)