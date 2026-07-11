---
title: IHtmlOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры экспорта HTML.
type: docs
url: /ru/com.aspose.slides/ihtmloptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Представляет параметры экспорта HTML.
## Методы

| Метод | Описание |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Возвращает или задает шаблон HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Возвращает или задает шаблон HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Возвращает или задает параметры формата изображений слайдов. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Возвращает или задает параметры формата изображений слайдов. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [getJpegQuality()](#getJpegQuality--) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [getPicturesCompression()](#getPicturesCompression--) | Представляет уровень сжатия изображений. Чтение/запись [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Представляет уровень сжатия изображений. Чтение/запись [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Булевый флаг указывает, остаются ли обрезанные части частью документа. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Булевый флаг указывает, остаются ли обрезанные части частью документа. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True, чтобы исключить атрибуты width и height из SVG-контейнера — это сделает макет адаптивным. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True, чтобы исключить атрибуты width и height из SVG-контейнера — это сделает макет адаптивным. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Получает или задает значение, указывающее, рендерится ли текст без использования лигатур. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Получает или задает значение, указывающее, рендерится ли текст без использования лигатур. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Возвращает или задает шаблон HTML. Чтение/запись [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Возвращает:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Возвращает или задает шаблон HTML. Чтение/запись [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Возвращает или задает параметры формата изображений слайдов. Чтение/запись [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Возвращает:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Возвращает или задает параметры формата изображений слайдов. Чтение/запись [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Возвращает:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись byte.

--------------------

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию **95**.

**Возвращает:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись byte.

--------------------

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию **95**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Представляет уровень сжатия изображений. Чтение/запись [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Возвращает:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Представляет уровень сжатия изображений. Чтение/запись [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Булевый флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false — они будут сериализованы в документе (что может привести к увеличению размера файла). Чтение/запись boolean.

**Возвращает:**
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

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True, чтобы исключить атрибуты width и height из SVG-контейнера — это сделает макет адаптивным. False — иначе. Чтение/запись boolean.

**Возвращает:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True, чтобы исключить атрибуты width и height из SVG-контейнера — это сделает макет адаптивным. False — иначе. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Получает или задает значение, указывающее, рендерится ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию свойство установлено в false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Получает или задает значение, указывающее, рендерится ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию свойство установлено в false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращает:**
[IInkOptions](../../com.aspose.slides/iinkoptions)