---
title: OpenAIWebClient
second_title: Aspose.Slides для Java: справочник API
description: Встроенная реализация, подключающаяся к API OpenAI.
type: docs
url: /ru/com.aspose.slides/openaiwebclient/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Встроенная реализация [IAIWebClient](../../com.aspose.slides/iaiwebclient), которая подключается к API OpenAI.

## Конструкторы

| Constructor | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создает экземпляр веб-клиента OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента OpenAI, использующего внешне управляемый HttpClient. |

## Методы

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Создает экземпляр беседы. |
| [close()](#close--) | Освобождает ресурсы, используемые этим экземпляром. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Создает экземпляр веб-клиента OpenAI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Языковая модель OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI. |
| organizationId | java.lang.String | Идентификатор организации (необязательно). |

```csharp
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

Создает экземпляр веб-клиента OpenAI, использующего внешне управляемый HttpClient. Предоставленный HttpClient не уничтожается этим экземпляром и остается владельцем вызывающего кода.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Языковая модель OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI |
| organizationId | java.lang.String | Идентификатор организации (необязательно) |
| httpClient | java.net.HttpURLConnection | Экземпляр внешне управляемого HttpClient |

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

Отправляет инструкцию чата в модель ИИ, используя предоставленный экземпляр HttpConnection, и возвращает ответное сообщение на данную инструкцию.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Returns:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Создает экземпляр беседы. В отличие от обычных вызовов ИИ, беседы сохраняют весь контекст.

**Returns:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Освобождает ресурсы, используемые этим экземпляром.