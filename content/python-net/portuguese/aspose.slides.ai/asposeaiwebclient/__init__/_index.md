---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM. Este é o cliente usado pelo construtor sem parâmetros **SlidesAIAgent.#ctor**, portanto criá-lo explicitamente só é necessário ao passar o cliente para o construtor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** diretamente.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Cria uma instância do cliente web Aspose AI que se conecta a um endpoint URL personalizado. Use esta sobrecarga quando você tem um URL fornecido pela equipe Aspose.Slides; caso contrário, use a sobrecarga **AsposeAIWebClient.#ctor** com o URL padrão.


```python
def __init__(self, url):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| url | **str** | Endpoint URL do Aspose LLM, fornecido pela equipe Aspose.Slides. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL não pode ser None ou vazio. |



### Ver também
* classe [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)