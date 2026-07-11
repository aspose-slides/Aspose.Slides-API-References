---
title: AsposeAIWebClient
second_title: Referência da API Aspose.Slides para Java
description: Uma implementação interna que se conecta ao LLM próprio da Aspose.
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

Uma implementação interna [IAIWebClient](../../com.aspose.slides/iaiwebclient) que conecta ao LLM próprio da Aspose. Este é o cliente padrão usado pelo construtor sem parâmetros  SlidesAIAgent()  .

## Construtores

| Construtor | Descrição |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM usando um HttpClient gerenciado externamente. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada usando um HttpClient gerenciado externamente. |

## Métodos

| Método | Descrição |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Cria uma instância de conversa. |
| [dispose()](#dispose--) | Libera os recursos usados por esta instância. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM. Este é o cliente usado pelo construtor sem parâmetros  SlidesAIAgent() , portanto criá-lo explicitamente só é necessário ao passar o cliente diretamente para o construtor  SlidesAIAgent(IAIWebClient) .

```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Cria uma instância do cliente web Aspose AI que se conecta ao endpoint padrão do Aspose LLM usando um HttpClient gerenciado externamente. O HttpClient fornecido não é descartado por esta instância e permanece sob a propriedade do chamador.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpClient gerenciada externamente. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada. Use esta sobrecarga quando você tem uma URL fornecida pela equipe Aspose.Slides; caso contrário, use a sobrecarga AsposeAIWebClient() com a URL padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do endpoint do Aspose LLM, fornecida pela equipe Aspose.Slides. |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Cria uma instância do cliente web Aspose AI que se conecta a uma URL de endpoint personalizada usando um HttpClient gerenciado externamente. O HttpClient fornecido não é descartado por esta instância e permanece sob a propriedade do chamador. Use esta sobrecarga quando você tem uma URL fornecida pela equipe Aspose.Slides e deseja fornecer seu próprio HttpClient; se você precisar apenas do seu próprio HttpClient com a URL padrão, use a sobrecarga AsposeAIWebClient(HttpClient).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| url | java.lang.String | URL do endpoint do Aspose LLM, fornecida pela equipe Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Uma instância de HttpClient gerenciada externamente. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envia uma instrução de chat para o modelo de IA usando uma instância HttpConnection fornecida e devolve a mensagem de resposta para a instrução dada.

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

Cria uma instância de conversa. Ao contrário das chamadas de IA regulares, as conversas mantêm todo o contexto.

**Retorna:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Uma instância [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Libera os recursos usados por esta instância.