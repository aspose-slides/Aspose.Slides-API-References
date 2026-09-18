---
title: SlidesAIAgent constructor
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inicializa uma nova instância de [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent) usando o incorporado
[`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) com sua configuração padrão. O cliente se conecta ao LLM próprio da Aspose e não requer configuração adicional.
Para usar um cliente de IA diferente, use a sobrecarga **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** em vez disso.


```python
def __init__(self):
    ...
```



## __init__(self, ai_client) {#iaiwebclient}
Inicializa uma nova instância de [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent) com um cliente de IA personalizado.
Use esta sobrecarga para especificar o provedor de IA, fornecer seu próprio LLM ou personalizar a
conexão (por exemplo, fornecendo seu próprio `HttpClient`).
Qualquer implementação de [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) pode ser usada, incluindo:
* [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)


Para usar o incorporado [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) com sua configuração padrão,
use a sobrecarga **SlidesAIAgent.#ctor** em vez disso.


```python
def __init__(self, ai_client):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) | Instância do cliente de IA. Qualquer implementação de [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) pode ser usada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instância do cliente de IA não foi fornecida. |



### Ver também
* class [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)