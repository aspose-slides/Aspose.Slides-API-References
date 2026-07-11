---
title: IAIWebClient
second_title: Aspose.Slides для Android через Java API
description: Интерфейс AI Web клиента.
type: docs
url: /ru/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Интерфейс AI Web клиента. Этот интерфейс позволяет заменять различные модели языка ИИ. Классы, реализующие этот интерфейс, предполагается использовать вместе со SlidesAIAgent.
## Методы

| Метод | Описание |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет чат-инструкцию модели ИИ, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на данную инструкцию. |
| [createConversation()](#createConversation--) | Создаёт экземпляр разговора. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Отправляет чат-инструкцию модели ИИ, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на данную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которое должно быть обработано моделью ИИ. |

**Возвращаемое значение:**
java.lang.String — Сообщение, сгенерированное моделью ИИ в ответ на данную инструкцию.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Создаёт экземпляр разговора. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) — экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).