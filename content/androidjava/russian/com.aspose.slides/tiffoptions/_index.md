---
title: TiffOptions
second_title: Aspose.Slides для Android через Java API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате TIFF.
type: docs
url: /ru/com.aspose.slides/tiffoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Сохранение презентации в документ TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Создать экземпляр класса TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Установка типа сжатия
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Типы сжатия
>      // Default - Указывает схему сжатия по умолчанию (LZW).
>      // None - Указывает отсутствие сжатия.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Глубина зависит от типа сжатия и не может быть установлена вручную.
>      // Единица разрешения всегда равна 2 (точки на дюйм)
>      // Установка DPI изображения
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Установить размер изображения
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Сохранить презентацию в TIFF с указанным размером изображения
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat содержит следующие значения (как указано в документации):
>      //Format1bppIndexed; // 1 бит на пиксель, индексированный.
>      //Format4bppIndexed; // 4 бита на пиксель, индексированный.
>      //Format8bppIndexed; // 8 бит на пиксель, индексированный.
>      //Format24bppRgb; // 24 бита на пиксель, RGB.
>      //Format32bppArgb; // 32 бита на пиксель, ARGB.
> 
>      // Сохранить презентацию в TIFF с указанным размером изображения
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Конструктор по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, которые управляют внешним видом объектов Ink в экспортируемом документе. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. |
| [getImageSize()](#getImageSize--) | Указывает размер генерируемого изображения TIFF. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Указывает размер генерируемого изображения TIFF. |
| [getDpiX()](#getDpiX--) | Указывает горизонтальное разрешение в точках на дюйм. |
| [setDpiX(long value)](#setDpiX-long-) | Указывает горизонтальное разрешение в точках на дюйм. |
| [getDpiY()](#getDpiY--) | Указывает вертикальное разрешение в точках на дюйм. |
| [setDpiY(long value)](#setDpiY-long-) | Указывает вертикальное разрешение в точках на дюйм. |
| [getCompressionType()](#getCompressionType--) | Указывает тип сжатия. |
| [setCompressionType(int value)](#setCompressionType-int-) | Указывает тип сжатия. |
| [getPixelFormat()](#getPixelFormat--) | Указывает формат пикселей для генерируемых изображений. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Указывает формат пикселей для генерируемых изображений. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Указывает алгоритм преобразования цветного изображения в черно-белое. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Указывает алгоритм преобразования цветного изображения в черно-белое. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Конструктор по умолчанию.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Предоставляет параметры, которые управляют внешним видом объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
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
### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Указывает размер генерируемого изображения TIFF. Значение по умолчанию 0x0, что означает, что размеры генерируемого изображения будут рассчитаны на основе размера слайда презентации. Чтение/запись [Size](../../com.aspose.slides.android/size).

**Возвращаемое значение:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Указывает размер генерируемого изображения TIFF. Значение по умолчанию 0x0, что означает, что размеры генерируемого изображения будут рассчитаны на основе размера слайда презентации. Чтение/запись [Size](../../com.aspose.slides.android/size).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись long.

**Возвращаемое значение:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Указывает горизонтальное разрешение в точках на дюйм. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Указывает вертикальное разрешение в точках на дюйм. Чтение/запись long.

**Возвращаемое значение:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Указывает вертикальное разрешение в точках на дюйм. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Указывает тип сжатия. Чтение/запись [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Возвращаемое значение:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Указывает тип сжатия. Чтение/запись [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Указывает формат пикселей для генерируемых изображений. Чтение/запись [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Возвращаемое значение:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Указывает формат пикселей для генерируемых изображений. Чтение/запись [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
public final int getBwConversionMode()
```


Указывает алгоритм преобразования цветного изображения в черно-белое. Эта опция будет применяться только если CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) установлен на [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) или [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Чтение/запись [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). По умолчанию [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Указывает алгоритм преобразования цветного изображения в черно-белое. Эта опция будет применяться только если CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) установлен на [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) или [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Чтение/запись [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). По умолчанию [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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