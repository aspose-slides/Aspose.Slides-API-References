---
title: Audio
second_title: Aspose.Slides для справочника API Java
description: Представляет встроенный аудиофайл.
type: docs
url: /ru/com.aspose.slides/audio/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Представляет встроенный аудиофайл.
## Методы

| Метод | Описание |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает тип MIME аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Возвращает тип MIME аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Возвращает тип MIME аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Возвращает тип MIME аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод \#getStream.getStream, чтобы предотвратить ненужную загрузку данных аудио в память или даже исключение OutOfMemoryException. Только для чтения byte[].

**Возвращаемое значение:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования.

**Возвращаемое значение:**
java.io.InputStream - Поток для чтения.