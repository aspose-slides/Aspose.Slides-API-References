---
title: ISlidesPicture
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет изображение в презентации.
type: docs
url: /ru/com.aspose.slides/islidespicture/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Представляет изображение в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getImage()](#getImage--) | Возвращает или задает встроенное изображение. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Возвращает или задает встроенное изображение. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задает URL связанного изображения. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задает URL связанного изображения. |
| [getImageTransform()](#getImageTransform--) | Возвращает коллекцию эффектов трансформации изображения. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Возвращает или задает встроенное изображение. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

**Возвращаемое значение:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Возвращает или задает встроенное изображение. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает или задает URL связанного изображения. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Возвращает или задает URL связанного изображения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Возвращает коллекцию эффектов трансформации изображения. Только для чтения [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Возвращаемое значение:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)