---
title: SVGOptions
second_title: Aspose.Slides для Android через Java API Справочник
description: Представляет параметры SVG.
type: docs
url: /ru/com.aspose.slides/svgoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Представляет параметры SVG.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Инициализирует новый экземпляр класса SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Инициализирует новый экземпляр класса SVGOptions, задавая объект контроллера внедрения ссылок. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. |
| [getUseFrameSize()](#getUseFrameSize--) | Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Определяет, выполнять ли указанное вращение фигуры при рендеринге или нет. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Определяет, выполнять ли указанное вращение фигуры при рендеринге или нет. |
| [getVectorizeText()](#getVectorizeText--) | Определяет, будет ли текст на слайде сохранён как графика. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Определяет, будет ли текст на слайде сохранён как графика. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Возвращает или задаёт нижний предел разрешения для растеризации метафайлов. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Возвращает или задаёт нижний предел разрешения для растеризации метафайлов. |
| [getDisable3DText()](#getDisable3DText--) | Определяет, отключён ли 3D-текст в SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Определяет, отключён ли 3D-текст в SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Отключает разбиение градиентов FromCornerX и FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Отключает разбиение градиентов FromCornerX и FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. |
| [getDefault()](#getDefault--) | Возвращает настройки по умолчанию. |
| [getSimple()](#getSimple--) | Возвращает настройки для создания самого простого и небольшого SVG-файла. |
| [getWYSIWYG()](#getWYSIWYG--) | Возвращает настройки для создания наиболее точного SVG-файла. |
| [getJpegQuality()](#getJpegQuality--) | Определяет качество кодирования JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Определяет качество кодирования JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. |
| [getPicturesCompression()](#getPicturesCompression--) | Представляет уровень сжатия изображений |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Представляет уровень сжатия изображений |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Определяет способ обработки внешне загруженных шрифтов. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Определяет способ обработки внешне загруженных шрифтов. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Получает или задаёт значение, указывающее, рендерится ли текст без использования лигатур. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Получает или задаёт значение, указывающее, рендерится ли текст без использования лигатур. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Инициализирует новый экземпляр класса SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Инициализирует новый экземпляр класса SVGOptions, задавая объект контроллера внедрения ссылок.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Ссылка на контроллер внедрения ссылок. |

--------------------

Контроллер внедрения ссылок — это делегат, отвечающий за принятие решений о том, должны ли ресурсы (например, изображения) быть внедрены или ссылаться как внешние ресурсы. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. Чтение/запись boolean. Значение по умолчанию — false.

**Возвращаемое значение:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. Чтение/запись boolean. Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Определяет, выполнять ли указанное вращение фигуры при рендеринге или нет. Чтение/запись boolean. Значение по умолчанию — true.

**Возвращаемое значение:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Определяет, выполнять ли указанное вращение фигуры при рендеринге или нет. Чтение/запись boolean. Значение по умолчанию — true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Определяет, будет ли текст на слайде сохранён как графика. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Определяет, будет ли текст на слайде сохранён как графика. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Возвращает или задаёт нижний предел разрешения для растеризации метафайлов. Чтение/запись int.

**Возвращаемое значение:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Возвращает или задаёт нижний предел разрешения для растеризации метафайлов. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Определяет, отключён ли 3D-текст в SVG. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Определяет, отключён ли 3D-текст в SVG. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Отключает разбиение градиентов FromCornerX и FromCenter. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Отключает разбиение градиентов FromCornerX и FromCenter. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

В SVG 1.1 отсутствует возможность задавать отступы для маркеров. Движок записи SVG в Aspose.Slides имеет обходной путь: он обрезает конец линии со стрелкой, чтобы линия не перекрывала маркеры. Эта опция отключает такое поведение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

В SVG 1.1 отсутствует возможность задавать отступы для маркеров. Движок записи SVG в Aspose.Slides имеет обходной путь: он обрезает конец линии со стрелкой, чтобы линия не перекрывала маркеры. Эта опция отключает такое поведение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Возвращает настройки по умолчанию. Только для чтения [SVGOptions](../../com.aspose.slides/svgoptions).

**Возвращаемое значение:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Возвращает настройки для создания самого простого и небольшого SVG-файла. Только для чтения [SVGOptions](../../com.aspose.slides/svgoptions).

**Возвращаемое значение:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Возвращает настройки для создания наиболее точного SVG-файла. Только для чтения [SVGOptions](../../com.aspose.slides/svgoptions).

**Возвращаемое значение:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Определяет качество кодирования JPEG. Чтение/запись int.

**Возвращаемое значение:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Определяет качество кодирования JPEG. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. Чтение/запись [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Возвращаемое значение:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. Чтение/запись [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Представляет уровень сжатия изображений

**Возвращаемое значение:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Представляет уровень сжатия изображений

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены; если false, они будут сериализованы в документе (что может привести к увеличению размера файла)

**Возвращаемое значение:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены; если false, они будут сериализованы в документе (что может привести к увеличению размера файла)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Определяет способ обработки внешне загруженных шрифтов. Чтение/запись [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Возвращаемое значение:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Определяет способ обработки внешне загруженных шрифтов. Чтение/запись [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Получает или задаёт значение, указывающее, рендерится ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию значение false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Получает или задаёт значение, указывающее, рендерится ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию значение false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |