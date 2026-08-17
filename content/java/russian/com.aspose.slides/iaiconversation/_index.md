---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Представляет экземпляр диалога.
type: docs
url: /ru/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Представляет экземпляр диалога. В отличие от обычных вызовов ИИ, диалоги сохраняют весь контекст.
## Методы

| Метод | Описание |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Отправляет запрос сообщения разговора, включая весь контекст, и возвращает ответ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Отправляет запрос сообщения разговора, включая весь контекст, и возвращает ответ.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| instruction | java.lang.String | Инструкция или сообщение, которое будет обработано моделью ИИ. |

**Возвращаемое значение:**
java.lang.String - Сообщение, сгенерированное моделью ИИ в ответ на данную инструкцию в контексте разговора.