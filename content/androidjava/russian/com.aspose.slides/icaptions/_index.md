---
title: ICaptions
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет закрытые субтитры WebVTT.
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
| [getLabel()](#getLabel--) | Возвращает или задает метку закрытых субтитров. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Возвращает или задает метку закрытых субтитров. |
| [getBinaryData()](#getBinaryData--) | Возвращает бинарные данные закрытых субтитров. |
| [getDataAsString()](#getDataAsString--) | Возвращает данные закрытых субтитров как строку, кодированную в UTF-8, Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. Read-only java.util.UUID.

**Возвращает:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Возвращает или задает метку закрытых субтитров. Read/write String.

**Возвращает:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Возвращает или задает метку закрытых субтитров. Read/write String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Возвращает бинарные данные закрытых субтитров. Read-only byte[].

**Возвращает:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Возвращает данные закрытых субтитров как строку, кодированную в UTF-8, Read-only String.

**Возвращает:**
java.lang.String