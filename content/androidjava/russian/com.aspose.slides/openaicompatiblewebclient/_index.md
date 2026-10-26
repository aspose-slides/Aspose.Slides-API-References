---
title: OpenAICompatibleWebClient
second_title: Aspose.Slides для Android через справку Java API
description: Встроенная реализация, которая подключается к поставщику LLM, совместимому с OpenAI, по указанному базовому URL.
type: docs
url: /ru/com.aspose.slides/openaicompatiblewebclient/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Встроенная реализация [IAIWebClient](../../com.aspose.slides/iaiwebclient), которая подключается к поставщику LLM, совместимому с OpenAI, по указанному базовому URL.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создаёт экземпляр веб-клиента, совместимого с OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создаёт экземпляр веб-клиента, совместимого с OpenAI, который использует управляемый извне HttpURLConnection. |

## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет инструкцию чата модели ИИ, используя управляемый извне экземпляр HttpURLConnection, и возвращает ответное сообщение на данную инструкцию. |
| [createConversation()](#createConversation--) | Создаёт экземпляр беседы. |
| [dispose()](#dispose--) | Освобождает ресурсы, использованные этим экземпляром. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Создаёт экземпляр веб-клиента, совместимого с OpenAI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Имя модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL LLM, совместимого с OpenAI. |

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

Создаёт экземпляр веб-клиента, совместимого с OpenAI, который использует управляемый извне HttpURLConnection. Предоставленный HttpURLConnection не освобождается этим экземпляром и остаётся во владении вызывающего кода.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Имя модели, поддерживаемой поставщиком LLM. |
| apiKey | java.lang.String | Ключ API (токен). |
| baseUrl | java.lang.String | Базовый URL LLM, совместимого с OpenAI. |
| httpClient | java.net.HttpURLConnection | Экземпляр HttpURLConnection, управляемый извне. |

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

Отправляет инструкцию чата модели ИИ, используя управляемый извне экземпляр HttpURLConnection, и возвращает ответное сообщение на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, обрабатываемое моделью ИИ. |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью ИИ в ответ на данную инструкцию.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Создаёт экземпляр беседы. В отличие от обычных вызовов ИИ, беседы сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает ресурсы, использованные этим экземпляром.