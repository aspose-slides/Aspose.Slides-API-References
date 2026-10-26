---
title: IXpsOptions
second_title: Справочник API Aspose.Slides для Java
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате XPS.
type: docs
url: /ru/com.aspose.slides/ixpsoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате XPS.
## Методы

| Метод | Описание |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, чтобы нарисовать черную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, чтобы нарисовать черную рамку вокруг каждого слайда. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать в сгенерированный документ скрытые слайды. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать в сгенерированный документ скрытые слайды. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись, логический тип.

--------------------

По умолчанию **true**.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись, логический тип.

--------------------

По умолчанию **true**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, чтобы нарисовать черную рамку вокруг каждого слайда. Чтение/запись, логический тип.

--------------------

По умолчанию **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, чтобы нарисовать черную рамку вокруг каждого слайда. Чтение/запись, логический тип.

--------------------

По умолчанию **false**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать в сгенерированный документ скрытые слайды. По умолчанию **false**.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать в сгенерированный документ скрытые слайды. По умолчанию **false**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |