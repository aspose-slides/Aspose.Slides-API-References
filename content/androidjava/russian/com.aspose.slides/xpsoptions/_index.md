---
title: XpsOptions
second_title: Справочник API Aspose.Slides для Android на Java
description: Предоставляет параметры, контролирующие способ сохранения презентации в формате XPS.
type: docs
url: /ru/com.aspose.slides/xpsoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Сохранение презентации в документ XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Создать экземпляр класса TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Сохранить MetaFiles как PNG
>      options.setSaveMetafilesAsPng(true);
>      // Сохранить презентацию в документ XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Конструктор по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в создаваемый документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в создаваемый документ. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True to convert all metafiles used in a presentation to the PNG images. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True to convert all metafiles used in a presentation to the PNG images. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True to draw black frame around each slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True to draw black frame around each slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Конструктор по умолчанию.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Указывает, следует ли включать скрытые слайды в создаваемый документ. По умолчанию false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Указывает, следует ли включать скрытые слайды в создаваемый документ. По умолчанию false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

По умолчанию **true**.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

По умолчанию **true**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True to draw black frame around each slide. Read/write boolean.

--------------------

По умолчанию **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True to draw black frame around each slide. Read/write boolean.

--------------------

По умолчанию **false**.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |