---
title: ImageCollection
second_title: Aspose.Slides для Android через Java справочник API
description: Представляет коллекцию PPImage.
type: docs
url: /ru/com.aspose.slides/imagecollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Представляет коллекцию PPImage.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество изображений в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Добавляет копию изображения из другой презентации. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Добавляет изображение в презентацию. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Добавляет изображение в презентацию из потока. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Создает и добавляет изображение в презентацию из потока. |
| [addImage(byte[] buffer)](#addImage-byte---) | Добавляет изображение в презентацию из указанного буфера. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Добавляет изображение в презентацию из объекта Svg. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корневой объект синхронизации. |
### size() {#size--}
```
public final int size()
```

Возвращает количество изображений в коллекции. Только для чтения  int .

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IPPImage](../../com.aspose.slides/ippimage).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Добавляет копию изображения из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Исходное изображение. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Добавляет изображение в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Изображение для добавления. |

---
This method converts WMF/EMF metafiles to raster PNG image before inserting to a presentation. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Добавляет изображение в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется изображение. |

---
This method can add WMF/EMF metafiles to a presentation without converting them to raster PNG image. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Создает и добавляет изображение в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого добавляется файл изображения. |
| loadingStreamBehavior | int | Поведение, которое будет применено к потоку. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавлен [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Добавляет изображение в презентацию из указанного буфера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Буфер. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Добавляет изображение в презентацию из объекта Svg.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Объект изображения Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Перечислитель, который можно использовать для прохода по коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - java.util.Iterator для всей коллекции.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения  boolean .

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корень синхронизации. Только для чтения  Object .

**Возвращаемое значение:**
java.lang.Object