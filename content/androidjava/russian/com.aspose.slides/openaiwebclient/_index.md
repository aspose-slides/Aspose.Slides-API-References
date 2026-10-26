---
title: OpenAIWebClient
second_title: Aspose.Slides для Android через справочник Java API
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

| Конструктор | Описание |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создаёт экземпляр веб-клиента OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создаёт экземпляр веб-клиента OpenAI, использующего внешне управляемый HttpClient . |
## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Создаёт экземпляр разговора. |
| [close()](#close--) | Освобождает ресурсы, используемые этим экземпляром. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Создаёт экземпляр веб-клиента OpenAI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Языковая модель OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI. |
| organizationId | java.lang.String | Идентификатор организации (необязательно). |

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

Создаёт экземпляр веб-клиента OpenAI, использующего внешне управляемый HttpClient . Предоставленный HttpClient не освобождается этим экземпляром и остаётся принадлежать вызывающему.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Языковая модель OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI |
| organizationId | java.lang.String | Идентификатор организации (необязательно) |
| httpClient | java.net.HttpURLConnection | Внешне управляемый экземпляр HttpClient |

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

Отправляет инструкцию чата модели ИИ, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Возвращает:**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Создаёт экземпляр разговора. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.

**Возвращает:**
[IAIConversation](../../com.aspose.slides/iaiconversation) — экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Освобождает ресурсы, используемые этим экземпляром.