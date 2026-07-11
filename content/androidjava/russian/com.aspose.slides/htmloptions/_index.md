---
title: HtmlOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры экспорта HTML.
type: docs
url: /ru/com.aspose.slides/htmloptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Представляет параметры экспорта HTML.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Создает новый объект HtmlOptions, указывая обратный вызов. |
| [HtmlOptions()](#HtmlOptions--) | Создает новый объект HtmlOptions для сохранения в один HTML-файл. |

## Методы

| Метод | Описание |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортированном документе. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в созданный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в созданный документ. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Получает или задает шаблон HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Получает или задает шаблон HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Получает или задает параметры формата изображений слайдов. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Получает или задает параметры формата изображений слайдов. |
| [getJpegQuality()](#getJpegQuality--) | Получает или задает значение, определяющее качество JPEG-изображений в документе PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Получает или задает значение, определяющее качество JPEG-изображений в документе PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Представляет уровень сжатия изображений |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Представляет уровень сжатия изображений |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Булевый флаг, указывающий, остаются ли обрезанные части частью документа. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True, чтобы исключить атрибуты width и height из контейнера svg — это сделает макет адаптивным. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True, чтобы исключить атрибуты width и height из контейнера svg — это сделает макет адаптивным. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Создает новый объект HtmlOptions, указывая обратный вызов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Объект обратного вызова, который управляет сохранением проекта. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Создает новый объект HtmlOptions для сохранения в один HTML-файл.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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


**Возвращаемое значение:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
public final IInkOptions getInkOptions()
```

Предоставляет параметры, контролирующие внешний вид объектов Ink в экспортированном документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в создаваемый документ. Значение по умолчанию — false.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в создаваемый документ. Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Получает или задает шаблон HTML. Чтение/запись [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Возвращаемое значение:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Получает или задает шаблон HTML. Чтение/запись [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию свойство имеет значение false.

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


**Возвращаемое значение:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Получает или задает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию свойство имеет значение false.

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

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Получает или задает параметры формата изображений слайдов. Чтение/запись [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Возвращаемое значение:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Получает или задает параметры формата изображений слайдов. Чтение/запись [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Получает или задает значение, определяющее качество JPEG-изображений в документе PDF. Чтение/запись byte.

--------------------

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или задать качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество при максимальном сжатии, а 100 — наилучшее качество при минимальном сжатии.

Значение по умолчанию — **95**.

**Возвращаемое значение:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Получает или задает значение, определяющее качество JPEG-изображений в документе PDF. Чтение/запись byte.

--------------------

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или задать качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество при максимальном сжатии, а 100 — наилучшее качество при минимальном сжатии.

Значение по умолчанию — **95**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

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

Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены; если false, они будут сериализованы в документе (что может привести к увеличению размера файла).

**Возвращаемое значение:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Булевый флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены; если false, они будут сериализованы в документе (что может привести к увеличению размера файла).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True, чтобы исключить атрибуты width и height из контейнера svg — это сделает макет адаптивным. False — иначе. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True, чтобы исключить атрибуты width и height из контейнера svg — это сделает макет адаптивным. False — иначе. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |