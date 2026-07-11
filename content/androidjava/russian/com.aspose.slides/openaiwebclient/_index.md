---
title: OpenAIWebClient
second_title: Aspose.Slides для Android через справочник Java API
description: Встроенный легковесный веб-клиент OpenAI
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

Встроенный легковесный клиент OpenAI web
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Создает экземпляр веб-клиента OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Создает экземпляр веб-клиента OpenAI. |
## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет инструкцию чата модели ИИ, используя внешне управляемый экземпляр, и возвращает ответное сообщение на данную инструкцию. |
| [createConversation()](#createConversation--) | Создает экземпляр разговора. |
| [close()](#close--) | Освобождает ресурсы, используемые этим экземпляром. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Создает экземпляр веб-клиента OpenAI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Модель языка OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI |
| organizationId | java.lang.String | Идентификатор организации (необязательно) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Создает экземпляр веб-клиента OpenAI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| model | java.lang.String | Модель языка OpenAI. Возможные значения: - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Ключ API OpenAI |
| organizationId | java.lang.String | Идентификатор организации (необязательно) |
| httpClient | java.net.HttpURLConnection | Внешне управляемый экземпляр HttpURLConnection. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Отправляет инструкцию чата модели ИИ, используя внешне управляемый экземпляр, и возвращает ответное сообщение на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которое будет обработано моделью ИИ |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью ИИ в ответ на данную инструкцию.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Создает экземпляр разговора. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Освобождает ресурсы, используемые этим экземпляром.