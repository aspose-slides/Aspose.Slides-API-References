---
title: GetRangeItemListLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string passada a partir da posição especificada para a coleção de instâncias da classe RangeItemHeaderValue.
type: docs
weight: 79
url: /pt/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) método

Converte uma string passada a partir da posição especificada para a coleção de instâncias da classe RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Uma instância onde a coleção analisada será atribuída. |

### Valor de Retorno

O comprimento de uma substring analisada, caso contrário 0.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ICollection](../../../system.collections.generic/icollection/)
* Classe [RangeItemHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)