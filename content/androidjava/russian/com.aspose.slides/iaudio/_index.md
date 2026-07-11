---  
title: IAudio  
second_title: Aspose.Slides for Android via Java API Reference  
description: Represents an embedded audio file.  
type: docs  
url: /ru/com.aspose.slides/iaudio/  
---```
public interface IAudio
```

Представляет встроенный аудиофайл.  
## Методы

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Возвращает MIME-тип аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Возвращает MIME-тип аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращаемое значение:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Возвращает копию данных аудио. При большом объёме данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать ненужной загрузки данных аудио в память или ошибки OutOfMemoryException. Только для чтения byte[].

**Возвращаемое значение:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования.

**Возвращаемое значение:**  
java.io.InputStream - Поток для чтения.