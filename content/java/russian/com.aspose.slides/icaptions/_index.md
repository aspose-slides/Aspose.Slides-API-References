---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /ru/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Представляет закрытые субтитры WebVTT.
## Методы

| Метод | Описание |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. |
| [getLabel()](#getLabel--) | Возвращает или задаёт метку закрытых субтитров. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Возвращает или задаёт метку закрытых субтитров. |
| [getBinaryData()](#getBinaryData--) | Возвращает двоичные данные закрытых субтитров. |
| [getDataAsString()](#getDataAsString--) | Возвращает данные закрытых субтитров как строку, закодированную в UTF-8. Только для чтения String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. Только для чтения java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Возвращает или задаёт метку закрытых субтитров. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Возвращает или задаёт метку закрытых субтитров. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Возвращает двоичные данные закрытых субтитров. Только для чтения byte[].

**Возвращаемое значение:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Возвращает данные закрытых субтитров как строку, закодированную в UTF-8. Только для чтения String.

**Возвращаемое значение:**
java.lang.String