---
title: Captions
second_title: Справочник API Aspose.Slides для Java
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

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Возвращает глобальный уникальный идентификатор (GUID) закрытых субтитров. |
| [getLabel()](#getLabel--) | Возвращает или задает метку закрытых субтитров. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Возвращает или задает метку закрытых субтитров. |
| [getBinaryData()](#getBinaryData--) | Возвращает бинарные данные закрытых субтитров. |
| [getDataAsString()](#getDataAsString--) | Возвращает данные закрытых субтитров как строку, закодированную в UTF-8. Только для чтения String. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Возвращает бинарные данные закрытых субтитров. Только для чтения byte[] .

**Возвращаемое значение:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

Возвращает данные закрытых субтитров как строку, закодированную в UTF-8. Только для чтения String.

**Возвращаемое значение:**
java.lang.String