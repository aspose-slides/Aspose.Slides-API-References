---
title: IAudioCollection
second_title: Aspose.Slides для Android через Java API справочник
description: Представляет коллекцию встроенных аудиофайлов.
type: docs
url: /ru/com.aspose.slides/iaudiocollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Представляет коллекцию встроенных аудиофайлов.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Добавляет копию аудиофайла из другой презентации. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Создаёт и добавляет аудио в презентацию из потока. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Создаёт и добавляет аудио в презентацию из потока. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Создаёт и добавляет аудио в презентацию из массива байтов. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio)

### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Добавляет копию аудиофайла из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Исходный аудио. |

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.

### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Создаёт и добавляет аудио в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется аудио. |

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.

### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Создаёт и добавляет аудио в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется аудио. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) будет применён к потоку. |

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.

### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Создаёт и добавляет аудио в презентацию из массива байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| audioData | byte[] | Байты аудио. |

**Возврат:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.