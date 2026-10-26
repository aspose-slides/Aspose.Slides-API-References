---
title: IImageCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию PPImage.
type: docs
url: /ru/com.aspose.slides/iimagecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Представляет коллекцию PPImage.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает изображение по его индексу. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Добавляет изображение в презентацию. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Добавляет изображение в презентацию из потока. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Создает и добавляет изображение в презентацию из потока. |
| [addImage(byte[] buffer)](#addImage-byte---) | Добавляет изображение в презентацию из указанного буфера. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Добавляет копию изображения из другой презентации. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Добавляет изображение в презентацию из SVG-объекта. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Возвращает изображение по его индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Изображение.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Добавляет изображение в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Изображение для добавления.

--------------------

Этот метод преобразует метафайлы WMF/EMF в растровое изображение PNG перед вставкой в презентацию. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Добавляет изображение в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого нужно добавить изображение.

--------------------

Этот метод может добавить метафайлы WMF/EMF в презентацию без преобразования их в растровое изображение PNG. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Создает и добавляет изображение в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого будет добавлен файл изображения. |
| loadingStreamBehavior | int | Поведение, которое будет применено к потоку. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавлен [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Добавляет изображение в презентацию из указанного буфера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Буфер. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Добавляет копию изображения из другой презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Исходное изображение. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Добавляет изображение в презентацию из SVG-объекта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-изображение [ISvgImage](../../com.aspose.slides/isvgimage) |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.