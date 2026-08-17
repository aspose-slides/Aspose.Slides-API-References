---
title: OpenAICompatibleWebClient
second_title: Справочник API Aspose.Slides для Java
description: Встроенная реализация, которая подключается к совместимому с OpenAI поставщику LLM по указанному базовому URL.
type: docs
url: /ru/com.aspose.slides/openaicompatiblewebclient/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Встроенная [IAIWebClient](../../com.aspose.slides/iaiwebclient) реализация, которая подключается к совместимому с OpenAI поставщику LLM по указанному базовому URL.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создаёт экземпляр совместимого с OpenAI веб-клиента. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создаёт экземпляр совместимого с OpenAI веб-клиента, использующего внешне управляемый HttpURLConnection. |
## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет инструкцию чата модели ИИ, используя внешне управляемый экземпляр HttpURLConnection, и возвращает сообщение-ответ на данную инструкцию. |
| [createConversation()](#createConversation--) | Создаёт экземпляр разговора. |
| [dispose()](#dispose--) | Освобождает ресурсы, используемые этим экземпляром. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Создаёт экземпляр совместимого с OpenAI веб-клиента.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Имя модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL совместимого с OpenAI LLM. |
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

Создаёт экземпляр совместимого с OpenAI веб-клиента, использующего внешне управляемый HttpURLConnection. Предоставленный HttpURLConnection не будет освобожден этим экземпляром и остаётся под управлением вызывающего кода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Имя модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL совместимого с OpenAI LLM. |
| httpClient | java.net.HttpURLConnection | Внешне управляемый экземпляр HttpURLConnection. |
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

Отправляет инструкцию чата модели ИИ, используя внешне управляемый экземпляр HttpURLConnection, и возвращает сообщение-ответ на данную инструкцию.

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

Создаёт экземпляр разговора. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает ресурсы, используемые этим экземпляром.