---
title: AsposeAIWebClient
second_title: Referência da API Aspose.Slides para Java
description: Uma implementação incorporada que se conecta ao próprio LLM da Aspose.
type: docs
url: /pt/com.aspose.slides/asposeaiwebclient/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Uma implementação [IAIWebClient](../../com.aspose.slides/iaiwebclient) incorporada que se conecta ao próprio LLM da Aspose. Este é o cliente padrão usado pelo construtor sem parâmetros SlidesAIAgent().

## Construtores

| Construtor | Descrição |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM usando um HttpURLConnection gerenciado externamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada usando um HttpURLConnection gerenciado externamente. |

## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envia uma instrução de chat ao modelo de IA e devolve a mensagem de resposta à instrução fornecida. |
| [createConversation()](#createConversation--) | Cria uma instância de conversa. |
| [dispose()](#dispose--) | Libera os recursos usados por esta instância. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM. Este é o cliente usado pelo construtor sem parâmetros SlidesAIAgent(), portanto criá-lo explicitamente só é necessário ao passar o cliente para o construtor SlidesAIAgent(IAIWebClient) diretamente.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM usando um HttpURLConnection gerenciado externamente. O HttpURLConnection fornecido não é descartado por esta instância e permanece sob responsabilidade do chamador.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpURLConnection gerenciada externamente.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada. Use esta sobrecarga quando você tem uma URL fornecida pela equipe Aspose.Slides; caso contrário, use a sobrecarga AsposeAIWebClient() com a URL padrão.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do endpoint do Aspose LLM, fornecida pela equipe Aspose.Slides.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada usando um HttpURLConnection gerenciado externamente. O HttpURLConnection fornecido não é descartado por esta instância e permanece sob responsabilidade do chamador. Use esta sobrecarga quando você tem uma URL fornecida pela equipe Aspose.Slides e deseja fornecer seu próprio HttpURLConnection; se você precisar apenas do seu HttpURLConnection com a URL padrão, use a sobrecarga AsposeAIWebClient(HttpURLConnection) em vez disso.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do endpoint do Aspose LLM, fornecida pela equipe Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpURLConnection gerenciada externamente.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

Envia uma instrução de chat ao modelo de IA e devolve a mensagem de resposta à instrução fornecida.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| instruction | java.lang.String | A instrução ou mensagem a ser processada pelo modelo de IA. |

**Retorna:**
java.lang.String - A mensagem gerada pelo modelo de IA em resposta à instrução fornecida.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Cria uma instância de conversa. Ao contrário das chamadas regulares de IA, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Libera os recursos usados por esta instância.