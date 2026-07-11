---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides para Referência da API Java
description: Uma implementação interna que conecta a um provedor LLM compatível com OpenAI em uma URL base especificada.
type: docs
url: /pt/com.aspose.slides/openaicompatiblewebclient/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) interna que conecta a um provedor LLM compatível com OpenAI em uma URL base especificada.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Cria uma instância do cliente web compatível com OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web compatível com OpenAI que utiliza um HttpClient gerenciado externamente. |
## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Cria uma instância de conversa. |
| [dispose()](#dispose--) | Libera os recursos usados por esta instância. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```


Cria uma instância do cliente web compatível com OpenAI.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Nome do modelo suportado pelo provedor LLM. |
| apiKey | java.lang.String | chave de API (token). |
| baseUrl | java.lang.String | URL base do LLM compatível com OpenAI.

```
using (OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1"))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```


Cria uma instância do cliente web compatível com OpenAI que utiliza um HttpClient gerenciado externamente. O HttpClient fornecido não é descartado por esta instância e permanece sob responsabilidade do chamador.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Nome do modelo suportado pelo provedor LLM. |
| apiKey | java.lang.String | chave de API (token). |
| baseUrl | java.lang.String | URL base do LLM compatível com OpenAI. |
| httpClient | java.net.HttpURLConnection | Instância de HttpClient gerenciada externamente.

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAICompatibleWebClient aiClient = new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Envia uma instrução de chat ao modelo de IA usando a instância HttpConnection fornecida e retorna a mensagem de resposta para a instrução dada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Retorna:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```


Cria uma instância de conversa. Diferentemente das chamadas regulares de IA, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```


Libera os recursos usados por esta instância.