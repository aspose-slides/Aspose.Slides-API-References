---
title: AsposeAIWebClient
second_title: Aspose.Slides для Android через справочник Java API
description: Встроенная реализация, которая подключается к собственному LLM Aspose.
type: docs
url: /ru/com.aspose.slides/asposeaiwebclient/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Встроенная реализация [IAIWebClient](../../com.aspose.slides/iaiwebclient), которая подключается к собственному LLM от Aspose. Это клиент по умолчанию, используемый параметром без аргументов конструктора SlidesAIAgent().

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке Aspose LLM по умолчанию. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке Aspose LLM по умолчанию, используя внешне управляемый HttpURLConnection. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки, используя внешне управляемый HttpURLConnection. |

## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет инструкцию чата модели ИИ и возвращает ответное сообщение на данную инструкцию. |
| [createConversation()](#createConversation--) | Создает экземпляр беседы. |
| [dispose()](#dispose--) | Освобождает ресурсы, используемые этим экземпляром. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке Aspose LLM по умолчанию. Этот клиент используется параметром без аргументов конструктора SlidesAIAgent(), поэтому создавать его явно необходимо лишь при прямой передаче клиента в конструктор SlidesAIAgent(IAIWebClient).

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

Создает экземпляр веб-клиента Aspose AI, который подключается к конечной точке Aspose LLM по умолчанию, используя внешне управляемый HttpURLConnection. Предоставленный HttpURLConnection не освобождается этим экземпляром и остаётся в собственности вызывающего кода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Экземпляр внешне управляемого HttpURLConnection. |

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

Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки. Используйте эту перегрузку, если у вас есть URL, предоставленный командой Aspose.Slides; в противном случае используйте перегрузку AsposeAIWebClient() с URL по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL конечной точки Aspose LLM, предоставленный командой Aspose.Slides. |

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

Создает экземпляр веб-клиента Aspose AI, который подключается к пользовательскому URL конечной точки, используя внешне управляемый HttpURLConnection. Предоставленный HttpURLConnection не освобождается этим экземпляром и остаётся в собственности вызывающего кода. Используйте эту перегрузку, если у вас есть URL, предоставленный командой Aspose.Slides, и вы хотите предоставить свой собственный HttpURLConnection; если вам нужен только свой HttpURLConnection с URL по умолчанию, используйте перегрузку AsposeAIWebClient(HttpURLConnection).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| url | java.lang.String | URL конечной точки Aspose LLM, предоставленный командой Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Экземпляр внешне управляемого HttpURLConnection. |

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

Отправляет инструкцию чата модели ИИ и возвращает ответное сообщение на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которые будут обработаны моделью ИИ. |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью ИИ в ответ на данную инструкцию.

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Создает экземпляр беседы. В отличие от обычных вызовов ИИ, беседы сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает ресурсы, используемые этим экземпляром.