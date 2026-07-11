---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides для Java: справочник API
description: Встроенная реализация, которая подключается к поставщику LLM, совместимому с OpenAI, по указанному базовому URL.
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

Встроенная [IAIWebClient](../../com.aspose.slides/iaiwebclient) реализация, которая подключается к поставщику LLM, совместимому с OpenAI, по указанному базовому URL.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создает экземпляр веб-клиента, совместимого с OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента, совместимого с OpenAI, использующего внешне управляемый HttpClient . |
## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Создает экземпляр беседы. |
| [dispose()](#dispose--) | Освобождает ресурсы, используемые этим экземпляром. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Создает экземпляр веб-клиента, совместимого с OpenAI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Название модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL совместимого с OpenAI LLM. |
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

Создает экземпляр веб-клиента, совместимого с OpenAI, использующего внешне управляемый HttpClient . Предоставленный HttpClient не будет освобождён этим экземпляром и остаётся в собственности вызывающего кода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Название модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL совместимого с OpenAI LLM. |
| httpClient | java.net.HttpURLConnection | Внешне управляемый экземпляр HttpClient. |
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

Отправляет чат-инструкцию модели ИИ, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String |  |
**Возвращаемое значение:**
java.lang.String
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