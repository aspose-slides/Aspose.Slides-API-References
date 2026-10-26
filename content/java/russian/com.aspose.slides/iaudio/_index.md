---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Представляет встроенный аудиофайл.
type: docs
url: /ru/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Представляет встроенный аудиофайл.
## Методы

| Метод | Описание |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает MIME-тип аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Возвращает MIME-тип аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращает:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Возвращает копию данных аудио. В случае большого объёма данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать лишней загрузки данных аудио в память или даже OutOfMemoryException. Только для чтения byte[].

**Возвращает:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования.

**Возвращает:**
java.io.InputStream - Stream for reading.