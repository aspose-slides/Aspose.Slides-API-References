---
title: ITiffOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.
type: docs
url: /ru/com.aspose.slides/itiffoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате TIFF.
## Методы

| Метод | Описание |
| --- | --- |
| [getImageSize()](#getImageSize--) | Указывает размер генерируемого изображения TIFF. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Указывает размер генерируемого изображения TIFF. |
| [getDpiX()](#getDpiX--) | Указывает горизонтальное разрешение в точках на дюйм. |
| [setDpiX(long value)](#setDpiX-long-) | Указывает горизонтальное разрешение в точках на дюйм. |
| [getDpiY()](#getDpiY--) | Указывает вертикальное разрешение в точках на дюйм. |
| [setDpiY(long value)](#setDpiY-long-) | Указывает вертикальное разрешение в точках на дюйм. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [getCompressionType()](#getCompressionType--) | Указывает тип сжатия. |
| [setCompressionType(int value)](#setCompressionType-int-) | Указывает тип сжатия. |
| [getPixelFormat()](#getPixelFormat--) | Указывает формат пикселей для генерируемых изображений. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Указывает формат пикселей для генерируемых изображений. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Указывает алгоритм преобразования цветного изображения в черно-белое. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Указывает алгоритм преобразования цветного изображения в черно-белое. |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Указывает размер генерируемого изображения TIFF. Значение по умолчанию — 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе размера слайда презентации. Чтение/запись [Size](../../com.aspose.slides.android/size).

**Возвращаемое значение:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Указывает размер генерируемого изображения TIFF. Значение по умолчанию — 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе размера слайда презентации. Чтение/запись [Size](../../com.aspose.slides.android/size).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись long.

**Возвращаемое значение:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Указывает вертикальное разрешение в точках на дюйм. Чтение/запись long.

**Возвращаемое значение:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Указывает вертикальное разрешение в точках на дюйм. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. Значение по умолчанию — false.

**Возвращаемое значение:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Указывает тип сжатия. Чтение/запись [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Возвращаемое значение:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Указывает тип сжатия. Чтение/запись [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Указывает формат пикселей для генерируемых изображений. Чтение/запись [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Возвращаемое значение:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Указывает формат пикселей для генерируемых изображений. Чтение/запись [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

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
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
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
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр применяется только если CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) установлен в [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) или [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Чтение/запись [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Значение по умолчанию — [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр применяется только если CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) установлен в [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) или [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Чтение/запись [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Значение по умолчанию — [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только чтение [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)