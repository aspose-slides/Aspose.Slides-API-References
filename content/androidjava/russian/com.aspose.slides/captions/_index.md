---
title: Captions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет закрытые субтитры WebVTT.
type: docs
url: /ru/com.aspose.slides/captions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Представляет закрытые субтитры WebVTT.
## Методы

| Метод | Описание |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. |
| [getLabel()](#getLabel--) | Возвращает или задает метку закрытых субтитров. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Возвращает или задает метку закрытых субтитров. |
| [getBinaryData()](#getBinaryData--) | Возвращает бинарные данные закрытых субтитров. |
| [getDataAsString()](#getDataAsString--) | Возвращает данные закрытых субтитров в виде строки, закодированной в UTF-8. Только для чтения String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. Только для чтения java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Возвращает или задает метку закрытых субтитров. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Возвращает или задает метку закрытых субтитров. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Возвращает бинарные данные закрытых субтитров. Только для чтения  byte[] .

**Возвращаемое значение:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Возвращает данные закрытых субтитров в виде строки, закодированной в UTF-8. Только для чтения String.

**Возвращаемое значение:**
java.lang.String