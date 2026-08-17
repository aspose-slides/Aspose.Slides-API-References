---
title: XpsOptions
second_title: Справка API Aspose.Slides для Java
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате XPS.
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
>      // Сохранить метафайлы как PNG
>      options.setSaveMetafilesAsPng(true);
>      // Сохранение презентации в документ XPS
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
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, если необходимо рисовать черную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, если необходимо рисовать черную рамку вокруг каждого слайда. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Конструктор по умолчанию.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию false.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Возвращаемое значение:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, если необходимо преобразовать все метафайлы, использованные в презентации, в изображения PNG. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, если необходимо рисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, если необходимо рисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |