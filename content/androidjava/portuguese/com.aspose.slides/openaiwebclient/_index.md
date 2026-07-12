---
title: OpenAIWebClient
second_title: Aspose.Slides para Android via Referência da API Java
description: Cliente web OpenAI leve incorporado
type: docs
url: /pt/com.aspose.slides/openaiwebclient/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Cliente web OpenAI leve embutido
## Construtores

| Construtor | Descrição |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Cria uma instância do cliente web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web OpenAI. |
## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envia uma instrução de chat ao modelo de IA usando uma instância gerenciada externamente e retorna a mensagem de resposta à instrução fornecida. |
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
| apiKey | java.lang.String | Chave de API OpenAI |
| organizationId | java.lang.String | ID da organização (opcional) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```


Cria uma instância do cliente web OpenAI.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| model | java.lang.String | Modelo de linguagem OpenAI. Valores possíveis: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Chave de API OpenAI |
| organizationId | java.lang.String | ID da organização (opcional) |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpURLConnection gerenciada externamente. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```


Envia uma instrução de chat ao modelo de IA usando uma instância gerenciada externamente e retorna a mensagem de resposta à instrução fornecida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo de IA |

**Retorna:**
java.lang.String - A mensagem gerada pelo modelo de IA em resposta à instrução fornecida.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```


Cria uma instância de conversa. Ao contrário das chamadas regulares de IA, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância de [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```


Libera os recursos usados por esta instância.