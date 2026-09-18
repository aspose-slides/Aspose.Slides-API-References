---
title: generate_presentation method
second_title: Aspose.Slides para Python via API de Referência .NET
description: 
type: docs
url: /pt/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Gera uma instância de apresentação a partir de uma descrição em texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma necessário.

```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| description | **str** | O tópico, ideias, citações ou trechos de texto. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/pt/aspose.slides.ai/presentationcontentamounttype) | A quantidade de conteúdo na apresentação resultante. |

### Observações

O exemplo abaixo usa o [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) padrão, que é criado pelo construtor sem parâmetros **SlidesAIAgent.#ctor** e se conecta ao LLM próprio da Aspose.  
Para usar um provedor de IA diferente, forneça seu próprio LLM ou personalize a conexão (por exemplo, fornecendo seu próprio `HttpClient`), passe uma implementação [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) para o construtor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementações disponíveis incluem:
* [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | A instrução de chat de IA não pode ser None ou vazia. |

## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Gera uma instância de apresentação a partir de uma descrição em texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma necessário.

```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| description | **str** | O tópico, ideias, citações ou trechos de texto. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/pt/aspose.slides.ai/presentationcontentamounttype) | A quantidade de conteúdo na apresentação resultante. |
| presentation_template | [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) | Uma apresentação a ser usada como modelo para layout e design, substituindo o modelo padrão. |

### Observações

O exemplo abaixo usa o [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) padrão, que é criado pelo construtor sem parâmetros **SlidesAIAgent.#ctor** e se conecta ao LLM próprio da Aspose.  
Para usar um provedor de IA diferente, forneça seu próprio LLM ou personalize a conexão (por exemplo, fornecendo seu próprio `HttpClient`), passe uma implementação [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) para o construtor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementações disponíveis incluem:
* [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | O modelo de apresentação não foi fornecido. |
| **RuntimeError(Proxy error(ArgumentException))** | A instrução de chat de IA não pode ser None ou vazia. |

### Veja Também
* classe [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* enumeração [`PresentationContentAmountType`](/slides/python-net/pt/aspose.slides.ai/presentationcontentamounttype)
* classe [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)