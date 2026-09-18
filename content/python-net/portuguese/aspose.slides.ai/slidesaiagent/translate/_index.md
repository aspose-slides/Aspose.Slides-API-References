---
title: translate method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Traduz uma apresentação para o idioma especificado usando IA (versão síncrona).

```python
def translate(self, presentation, language):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) | Apresentação de destino |
| language | **str** | Idioma de destino |

### Observações
O exemplo abaixo usa o padrão [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient), que é criado pelo construtor sem parâmetros **SlidesAIAgent.#ctor** e conecta ao LLM próprio da Aspose. Para usar um provedor de IA diferente, forneça seu próprio LLM ou customize a conexão (por exemplo, fornecendo seu próprio `HttpClient`), passe uma implementação [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) para o construtor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementações disponíveis incluem:

* [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instância de apresentação não foi fornecida |
| **RuntimeError(Proxy error(ArgumentException))** | Valor do idioma não pode ser None ou vazio |

### Ver também
* classe [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)