---
title: get_object_storing_location method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Determina onde o objeto deve ser armazenado.  
Este método é chamado uma vez para cada id de objeto.  
Não há garantia de que não existam dois objetos com os mesmos dados, semanticName e contentType, mas com id diferente.

### Retorno

Decisão



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| id | **int** | Id do objeto. Este id é único em toda a operação de gravação. |
| entity_data | **bytes** | Dados binários do objeto. Este parâmetro pode ser None, se os dados binários do objeto ainda não foram gerados. |
| semantic_name | **str** | Algum texto curto que descreve o significado do objeto. O controlador pode usar isso como parte do nome externo do objeto, mas cabe ao despachante garantir que os nomes sejam únicos e contenham apenas caracteres permitidos. |
| content_type | **str** | Tipo MIME do objeto. |
| recomended_extension | **str** | Extensão de nome de arquivo, recomendada para este tipo MIME. |



### Veja Também
* classe [`ILinkEmbedController`](/slides/python-net/pt/aspose.slides.export/ilinkembedcontroller)
* enumeração [`LinkEmbedDecision`](/slides/python-net/pt/aspose.slides.export/linkembeddecision)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)