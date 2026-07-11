---
title: Picture
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет изображение в презентации.
type: docs
url: /ru/com.aspose.slides/picture/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Представляет изображение в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Возвращает или задаёт встроенное изображение. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Возвращает или задаёт встроенное изображение. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает или задаёт URL связанного изображения. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает или задаёт URL связанного изображения. |
| [getImageTransform()](#getImageTransform--) | Возвращает коллекцию эффектов трансформации изображения. |
| [getPresentation()](#getPresentation--) | Возвращает презентацию. |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает с указанным объектом. |
| [hashCode()](#hashCode--) | Возвращает хеш. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд изображения. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращает:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Возвращает или задаёт встроенное изображение. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

**Возвращает:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Возвращает или задаёт встроенное изображение. Чтение/запись [IPPImage](../../com.aspose.slides/ippimage).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Возвращает или задаёт URL связанного изображения. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Возвращает или задаёт URL связанного изображения. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Возвращает коллекцию эффектов трансформации изображения. Только для чтения [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Возвращает:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает презентацию. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Сравнивает с указанным объектом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращает:**
boolean - true, если объекты равны, иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Возвращает хеш.

**Возвращает:**
int – Хеш.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд изображения. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)