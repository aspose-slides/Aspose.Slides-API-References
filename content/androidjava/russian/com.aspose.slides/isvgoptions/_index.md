---
title: ISVGOptions
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет параметры SVG.
type: docs
url: /ru/com.aspose.slides/isvgoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Представляет параметры SVG.
## Методы

| Метод | Описание |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Определяет, будет ли текст на слайде сохраняться как графика. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Определяет, будет ли текст на слайде сохраняться как графика. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Возвращает или задает нижний предел разрешения для растризации метафайла. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Возвращает или задает нижний предел разрешения для растризации метафайла. |
| [getDisable3DText()](#getDisable3DText--) | Определяет, отключён ли 3D-текст в SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Определяет, отключён ли 3D-текст в SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Отключает разбиение градиентов FromCornerX и FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Отключает разбиение градиентов FromCornerX и FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. |
| [getJpegQuality()](#getJpegQuality--) | Определяет качество кодирования JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Определяет качество кодирования JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Возвращает и задает интерфейс обратного вызова, позволяющий пользователю контролировать преобразование фигур. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Возвращает и задает интерфейс обратного вызова, позволяющий пользователю контролировать преобразование фигур. |
| [getPicturesCompression()](#getPicturesCompression--) | Представляет уровень сжатия изображений Чтение/запись #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Представляет уровень сжатия изображений Чтение/запись #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Булевый флаг указывает, остаются ли обрезанные части частью документа. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Булевый флаг указывает, остаются ли обрезанные части частью документа. |
| [getUseFrameSize()](#getUseFrameSize--) | Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Определяет, выполнять ли заданное вращение фигуры при рендеринге или нет. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Определяет, выполнять ли заданное вращение фигуры при рендеринге или нет. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Определяет способ обработки внешне загруженных шрифтов. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Определяет способ обработки внешне загруженных шрифтов. |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Определяет, будет ли текст на слайде сохраняться как графика. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Определяет, будет ли текст на слайде сохраняться как графика. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Возвращает или задает нижний предел разрешения для растризации метафайла. Чтение/запись int.

**Возвращаемое значение:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Возвращает или задает нижний предел разрешения для растризации метафайла. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Определяет, отключён ли 3D-текст в SVG. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Определяет, отключён ли 3D-текст в SVG. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Отключает разбиение градиентов FromCornerX и FromCenter. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Отключает разбиение градиентов FromCornerX и FromCenter. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

В SVG 1.1 отсутствует возможность задавать отступы для маркеров. Движок записи SVG Aspose.Slides имеет обходное решение этой проблемы: он обрезает конец линии со стрелкой, поэтому линия не перекрывает маркеры. Эта опция отключает такое поведение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

В SVG 1.1 отсутствует возможность задавать отступы для маркеров. Движок записи SVG Aspose.Slides имеет обходное решение этой проблемы: он обрезает конец линии со стрелкой, поэтому линия не перекрывает маркеры. Эта опция отключает такое поведение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Определяет качество кодирования JPEG. Чтение/запись int.

**Возвращаемое значение:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Определяет качество кодирования JPEG. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Возвращает и задает интерфейс обратного вызова, позволяющий пользователю контролировать преобразование фигур. Чтение/запись [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Возвращаемое значение:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Возвращает и задает интерфейс обратного вызова, позволяющий пользователю контролировать преобразование фигур. Чтение/запись [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Представляет уровень сжатия изображений Чтение/запись #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Возвращаемое значение:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Представляет уровень сжатия изображений Чтение/запись #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Булевый флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false — они будут сериализованы в документе (что может привести к увеличению размера файла). Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Булевый флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false — они будут сериализованы в документе (что может привести к увеличению размера файла). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. Чтение/запись boolean. Значение по умолчанию — false.

**Возвращаемое значение:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Определяет, будет ли текстовый фрейм включён в область рендеринга или нет. Чтение/запись boolean. Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Определяет, выполнять ли заданное вращение фигуры при рендеринге или нет. Чтение/запись boolean. Значение по умолчанию — true.

**Возвращаемое значение:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Определяет, выполнять ли заданное вращение фигуры при рендеринге или нет. Чтение/запись boolean. Значение по умолчанию — true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Определяет способ обработки внешне загруженных шрифтов. Чтение/запись [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Возвращаемое значение:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Определяет способ обработки внешне загруженных шрифтов. Чтение/запись [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.

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
public abstract void setDisableFontLigatures(boolean value)
```

Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.

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