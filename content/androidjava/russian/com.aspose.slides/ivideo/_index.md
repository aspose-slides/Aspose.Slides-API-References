---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет видео, встроенное в презентацию.
type: docs
url: /ru/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Представляет видео, встроенное в презентацию.
## Методы

| Метод | Описание |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает MIME-type видео, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает Stream для чтения. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Возвращает MIME-type видео, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать ненужной загрузки данных видео в память или исключения OutOfMemoryException. Только для чтения byte[].

**Возвращаемое значение:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Возвращает Stream для чтения. Используйте «using» или закройте поток после использования.

**Возвращаемое значение:**
java.io.InputStream - Stream для чтения.