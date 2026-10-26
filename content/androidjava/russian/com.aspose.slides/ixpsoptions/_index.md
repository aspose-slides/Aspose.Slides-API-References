---
title: IXpsOptions
second_title: Aspose.Slides для Android через справочник Java API
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Истина, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Истина, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Истина, если необходимо рисовать черную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Истина, если необходимо рисовать черную рамку вокруг каждого слайда. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в генерируемый документ или нет. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в генерируемый документ или нет. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Истина, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись, boolean.

--------------------

По умолчанию **true**.

**Возвращаемое значение:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Истина, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись, boolean.

--------------------

По умолчанию **true**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Истина, если необходимо рисовать черную рамку вокруг каждого слайда. Чтение/запись, boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Истина, если необходимо рисовать черную рамку вокруг каждого слайда. Чтение/запись, boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в генерируемый документ или нет. По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в генерируемый документ или нет. По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |