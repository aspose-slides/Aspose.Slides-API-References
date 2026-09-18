---
title: AsposeAIWebClient class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient classe

Uma implementação [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) embutida que se conecta ao próprio LLM da Aspose.
            Este é o cliente padrão usado pelo construtor sem parâmetros **SlidesAIAgent.#ctor**.

O tipo AsposeAIWebClient expõe os seguintes membros:

## Construtores

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient/__init__/#) | Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM.<br/>            Este é o cliente usado pelo construtor sem parâmetros **SlidesAIAgent.#ctor**, portanto criar<br/>            explicitamente só é necessário ao passar o cliente para o construtor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            diretamente. |
| [`__init__(self, url)`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada. Use esta<br/>            sobrecarga quando você possui uma URL fornecida pela equipe Aspose.Slides; caso contrário, use a<br/>            sobrecarga **AsposeAIWebClient.#ctor** com a URL padrão. |

## Métodos

| Method | Description |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Cria uma instância de conversa. Diferente das chamadas regulares de IA, as conversas mantêm todo o contexto. |


### Ver também
* classe [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/pt/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)