---
title: SlidesAIAgent class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent classe

Fornece recursos baseados em IA para processar apresentações.

O tipo SlidesAIAgent expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inicializa uma nova instância de [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent) com um cliente de IA personalizado.<br/>            Use esta sobrecarga para especificar o provedor de IA, fornecer seu próprio LLM ou personalizar a<br/>            conexão (por exemplo, fornecendo seu próprio `HttpClient`).<br/>            Qualquer implementação de [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) pode ser usada, incluindo:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Para usar o [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) embutido com sua configuração padrão,<br/>            use a sobrecarga **SlidesAIAgent.#ctor** em vez disso. |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/__init__/#) | Inicializa uma nova instância de [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent) usando o [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient) embutido com sua configuração padrão. O cliente se conecta ao<br/>            LLM próprio da Aspose e não requer configuração adicional.<br/>            Para usar um cliente de IA diferente, use a sobrecarga **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** em vez disso. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma exigido. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Gera uma instância de apresentação a partir de uma descrição de texto. Forneça um tópico, ideias, citações ou trechos de texto no idioma exigido. |
| [`translate(self, presentation, language)`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Traduza uma apresentação para o idioma especificado usando IA (versão síncrona). |

### Ver também
* classe [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient)
* classe [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient)
* classe [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient)
* classe [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient)
* classe [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)