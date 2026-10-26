---
title: AudioCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию встроенных аудиофайлов.
type: docs
url: /ru/com.aspose.slides/audiocollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Представляет коллекцию встроенных аудиофайлов.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество аудиофайлов в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Добавляет копию аудиофайла из другой презентации. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Создаёт и добавляет аудио в презентацию из потока. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Создаёт и добавляет аудио в презентацию из потока. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Создаёт и добавляет аудио в презентацию из массива байтов. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует аудио в указанный массив, начиная с указанного индекса. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
### size() {#size--}
```
public final int size()
```

Возвращает количество аудиофайлов в коллекции. Только для чтения int.

**Возвращает:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IAudio](../../com.aspose.slides/iaudio).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Добавляет копию аудиофайла из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Источник аудио. |

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Создаёт и добавляет аудио в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавлять аудио. |

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Создаёт и добавляет аудио в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавить аудио. |
| loadingStreamBehavior | int | Поведение, которое будет применено к потоку. |

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Создаёт и добавляет аудио в презентацию из массива байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| audioData | byte[] | Байты аудио. |

**Возвращает:**
[IAudio](../../com.aspose.slides/iaudio) - Добавленное аудио.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует аудио в указанный массив, начиная с указанного индекса.

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

Возвращает корень синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - IGenericEnumerator, который можно использовать для перебора элементов коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - java.util.Iterator для всей коллекции.