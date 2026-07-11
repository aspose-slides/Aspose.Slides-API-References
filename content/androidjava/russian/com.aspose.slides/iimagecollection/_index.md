---
title: IImageCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию PPImage.
type: docs
url: /ru/com.aspose.slides/iimagecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Represents collection of PPImage.

## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает изображение по его индексу. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Добавляет изображение в презентацию. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Добавляет изображение в презентацию из потока. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Создаёт и добавляет изображение в презентацию из потока. |
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
[IPPImage](../../com.aspose.slides/ippimage) - Image.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Добавляет изображение в презентацию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Image to add.

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
| stream | java.io.InputStream | Stream to add image from.

--------------------
Этот метод может добавить метафайлы WMF/EMF в презентацию без их преобразования в растровое изображение PNG. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Добавленное изображение.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Создаёт и добавляет изображение в презентацию из потока.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add image file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Добавляет изображение в презентацию из указанного буфера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Adds a copy of an image from an another presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Source image. |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Add an image to a presentation from SVG object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG image object [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returns:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.