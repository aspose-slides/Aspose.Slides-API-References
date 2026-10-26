---
title: OpenAIWebClient constructor
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Cria uma instância do cliente web OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| model | **str** | Modelo de linguagem OpenAI. Valores possíveis:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Chave API da OpenAI. |
| organization_id | **str** | ID da organização (opcional). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | O valor da chave API não pode ser None ou vazio. |
| **RuntimeError(Proxy error(ArgumentException))** | O valor do modelo de texto não pode ser None ou vazio. |



### Veja Também
* classe [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)