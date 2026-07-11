---
title: Video
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет изображение, встроенное в презентацию.
type: docs
url: /ru/com.aspose.slides/video/
---
**Наследование:**  
java.lang.Object

**Все реализованные интерфейсы:**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

Представляет изображение, встроенное в презентацию.
## Методы

| Метод | Описание |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает MIME-тип видео, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Возвращает MIME-тип видео, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращаемое значение:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать ненужной загрузки данных видео в память или даже OutOfMemoryException. Только для чтения byte[].

**Возвращаемое значение:**  
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования.

**Возвращаемое значение:**  
java.io.InputStream – поток для чтения.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**  
com.aspose.slides.IDOMObject