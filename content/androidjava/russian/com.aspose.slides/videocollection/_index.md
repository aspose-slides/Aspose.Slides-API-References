---
title: VideoCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию объектов Video.
type: docs
url: /ru/com.aspose.slides/videocollection/
---
**Inheritance:**  
Наследование:  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
Все реализованные интерфейсы:  
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)  
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Представляет коллекцию объектов Video.

## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество видеофайлов в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Добавляет копию видеофайла из другой презентации. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Создаёт и добавляет видео в презентацию из потока. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Создаёт и добавляет видео в презентацию из массива байтов. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует видео в указанный массив, начиная с указанного индекса. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |

### size() {#size--}
```
public final int size()
```

Возвращает количество видеофайлов в коллекции. Только для чтения int.

**Возвращает:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IVideo](../../com.aspose.slides/ivideo).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo)

### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Добавляет копию видеофайла из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Исходное видео. |

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo) - Добавленное видео.

### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Создаёт и добавляет видео в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется видеофайл. |
| loadingStreamBehavior | int | Поведение, которое будет применено к потоку. |

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo) - Добавлен [IVideo](../../com.aspose.slides/ivideo).

### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Создаёт и добавляет видео в презентацию из массива байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| videoData | byte[] | Байты видео. |

**Возвращает:**
[IVideo](../../com.aspose.slides/ivideo) - Добавленное видео.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует видео в указанный массив, начиная с указанного индекса.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив. |
| index | int | Индекс. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращает:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Возвращает перечислитель, который перебирает коллекцию.

**Возвращает:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Перечислитель IGenericEnumerator, который можно использовать для перебора коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator для всей коллекции.