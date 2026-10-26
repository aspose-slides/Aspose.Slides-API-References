---
title: IVideoCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию объектов Video.
type: docs
url: /ru/com.aspose.slides/ivideocollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Представляет коллекцию объектов Video.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Добавляет копию видеофайла из другой презентации. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Создает и добавляет видео в презентацию из потока. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Создает и добавляет видео в презентацию из массива байтов. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Получает элемент по указанному индексу. Только для чтения [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Добавляет копию видеофайла из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Исходное видео. |

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo) - Добавленное видео.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Создает и добавляет видео в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется видеофайл. |
| loadingStreamBehavior | int | Поведение, которое будет применено к потоку. |

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo) - Добавлен [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Создает и добавляет видео в презентацию из массива байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| videoData | byte[] | Байты видео. |

**Возвращаемое значение:**
[IVideo](../../com.aspose.slides/ivideo) - Добавленное видео.