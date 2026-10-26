---
title: TryGetValues()
second_title: Referência da API Aspose.Slides para C++
description: Tenta obter os valores correspondentes pelo nome especificado.
type: docs
weight: 66
url: /pt/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) method


Tenta obter os valores correspondentes pelo nome especificado.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome do cabeçalho. |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Uma instância onde os valores correspondentes serão atribuídos. |

### Valor de Retorno

True quando os valores do cabeçalho são encontrados pelo nome especificado, caso contrário false.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)