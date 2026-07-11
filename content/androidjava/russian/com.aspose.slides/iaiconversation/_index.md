---
title: IAIConversation
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет экземпляр беседы.
type: docs
url: /ru/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Представляет экземпляр беседы. В отличие от обычных вызовов ИИ, разговоры сохраняют весь контекст.
## Методы

| Метод | Описание |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Отправляет сообщение запроса беседы, включая весь контекст, и возвращает ответ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Отправляет сообщение запроса беседы, включая весь контекст, и возвращает ответ.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которое будет обработано моделью ИИ. |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью ИИ в ответ на заданную инструкцию в контексте беседы.