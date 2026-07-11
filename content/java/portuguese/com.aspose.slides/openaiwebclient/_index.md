---
title: OpenAIWebClient
second_title: Referência da API Aspose.Slides para Java
description: Uma implementação interna que se conecta à API OpenAI.
type: docs
url: /pt/com.aspose.slides/openaiwebclient/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Uma implementação interna [IAIWebClient](../../com.aspose.slides/iaiwebclient) que se conecta à API OpenAI.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Cria uma instância do cliente web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web OpenAI que usa um HttpClient gerenciado externamente. |

## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Cria uma instância de conversa. |
| [close()](#close--) | Libera os recursos usados por esta instância. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Cria uma instância do cliente web OpenAI.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Modelo de linguagem OpenAI. Valores possíveis: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chave de API OpenAI. |
| organizationId | java.lang.String | ID da organização (opcional). |
```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Cria uma instância do cliente web OpenAI que usa um HttpClient gerenciado externamente. O HttpClient fornecido não é descartado por esta instância e permanece de responsabilidade do chamador.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Modelo de linguagem OpenAI. Valores possíveis: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chave de API OpenAI |
| organizationId | java.lang.String | ID da organização (opcional) |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpClient gerenciada externamente |
```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
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

Envia uma instrução de chat ao modelo de IA usando uma instância de HttpConnection fornecida e retorna a mensagem de resposta para a instrução dada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Retorna:**
java.lang.String

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Cria uma instância de conversa. Ao contrário das chamadas regulares de IA, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma [IAIConversation](../../com.aspose.slides/iaiconversation) instância.

### close() {#close--}
```
public final void close()
```

Libera os recursos usados por esta instância.