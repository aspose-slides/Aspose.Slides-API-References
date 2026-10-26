---
title: Audio
second_title: Aspose.Slides для Android через справочник Java API
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
| [getContentType()](#getContentType--) | Возвращает MIME-type аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Возвращает MIME-type аудио, закодированный в (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Возвращает копию данных аудио. |
| [getStream()](#getStream--) | Возвращает поток Stream для чтения. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Возвращает MIME-type аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Возвращает:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Возвращает MIME-type аудио, закодированный в (\#getBinaryData.getBinaryData). Только для чтения String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Возвращает копию данных аудио. При большом объёме данных рекомендуется использовать метод \#getStream.getStream, чтобы избежать ненужной загрузки данных аудио в память или исключения OutOfMemoryException. Только для чтения byte[].

**Возвращает:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Возвращает поток Stream для чтения. Используйте 'using' или закройте поток после использования.

**Возвращает:**
java.io.InputStream - поток для чтения.