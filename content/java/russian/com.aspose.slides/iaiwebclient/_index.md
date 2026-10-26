---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Интерфейс веб-клиента AI.
type: docs
url: /ru/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Веб-клиент AI. Этот интерфейс позволяет использовать различные модели AI для естественного языка. Классы, реализующие этот интерфейс, предполагается использовать совместно со SlidesAIAgent.

## Методы

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Отправляет инструкцию чата модели AI, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на заданную инструкцию. |
| [createConversation()](#createConversation--) | Создаёт экземпляр разговора. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Отправляет инструкцию чата модели AI, используя предоставленный экземпляр HttpConnection, и возвращает сообщение-ответ на заданную инструкцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которые будут обрабатываться моделью AI. |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью AI в ответ на заданную инструкцию.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Создаёт экземпляр разговора. В отличие от обычных вызовов AI, разговоры сохраняют весь контекст.

**Возвращаемое значение:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Экземпляр [IAIConversation](../../com.aspose.slides/iaiconversation).