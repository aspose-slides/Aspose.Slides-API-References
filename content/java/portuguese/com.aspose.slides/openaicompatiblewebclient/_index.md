---
title: OpenAICompatibleWebClient
second_title: Referência da API do Aspose.Slides para Java
description: Uma implementação interna que se conecta a um provedor LLM compatível com OpenAI em uma URL base especificada.
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

Uma implementação interna [IAIWebClient](../../com.aspose.slides/iaiwebclient) que se conecta a um provedor LLM compatível com OpenAI em uma URL base especificada.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Cria uma instância do cliente web compatível com OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web compatível com OpenAI que usa um HttpURLConnection gerenciado externamente . |
## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envia uma instrução de chat ao modelo de IA usando uma instância de HttpURLConnection gerenciada externamente e retorna a mensagem de resposta à instrução fornecida. |
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
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```


Cria uma instância do cliente web compatível com OpenAI que usa um HttpURLConnection gerenciado externamente . O HttpURLConnection fornecido não é descartado por esta instância e permanece sob responsabilidade do chamador.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Nome do modelo suportado pelo provedor LLM. |
| apiKey | java.lang.String | chave de API (token). |
| baseUrl | java.lang.String | URL base do LLM compatível com OpenAI. |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpURLConnection gerenciada externamente.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Envia uma instrução de chat ao modelo de IA usando uma instância de HttpURLConnection gerenciada externamente e retorna a mensagem de resposta à instrução fornecida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo de IA. |

**Retorna:**
java.lang.String - A mensagem gerada pelo modelo de IA em resposta à instrução fornecida.
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```


Cria uma instância de conversa. Ao contrário das chamadas regulares de IA, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```


Libera os recursos usados por esta instância.