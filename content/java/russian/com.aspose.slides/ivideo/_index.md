---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Представляет видео, встроенное в презентацию.
type: docs
url: /ru/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Представляет видео, встроенное в презентацию.
## Methods

| Метод | Описание |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает MIME-type видео, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Возвращает MIME-type видео, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращает:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать ненужной загрузки данных видео в память или даже OutOfMemoryException. Только для чтения byte[].

**Возвращает:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Возвращает поток Stream для чтения. Используйте 'using' или закрывайте поток после использования.

**Возвращает:**
java.io.InputStream - поток для чтения.