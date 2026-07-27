---
title: GetEntityTagLength()
second_title: Referência da API Aspose.Slides para C++
description: Converte uma string passada a partir do índice especificado para uma instância da classe EntityTagHeaderValue.
type: docs
weight: 118
url: /pt/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) método

Converte uma string passada do índice especificado para uma instância da classe [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | [String](../../../system/string/) | Uma string a ser analisada. |
| startIndex | **int32_t** | Uma posição inicial para análise. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Uma instância onde um objeto analisado será atribuído. |

### Valor de Retorno

O comprimento de uma substring analisada, caso contrário 0.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [EntityTagHeaderValue](../)
* Espaço de nomes [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)