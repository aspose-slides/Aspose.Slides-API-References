---
title: IPdfOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате PDF.
type: docs
url: /ru/com.aspose.slides/ipdfoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Предоставляет параметры, управляющие тем, как презентация сохраняется в формате PDF.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [setTextCompression(int value)](#setTextCompression-int-) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True, чтобы встраивать TrueType-шрифты для ASCII-символов 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True, чтобы встраивать TrueType-шрифты для ASCII-символов 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в генерируемый документ. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides следует считать общими. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides следует считать общими. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранять его в PDF, когда шрифт не поддерживает полужирное начертание. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранять его в PDF, когда шрифт не поддерживает полужирное начертание. |
| [getJpegQuality()](#getJpegQuality--) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [getCompliance()](#getCompliance--) | Желаемый уровень соответствия для генерируемого PDF-документа. |
| [setCompliance(int value)](#setCompliance-int-) | Желаемый уровень соответствия для генерируемого PDF-документа. |
| [getPassword()](#getPassword--) | Установка пользовательского пароля для защиты PDF-документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установка пользовательского пароля для защиты PDF-документа. |
| [getAccessPermissions()](#getAccessPermissions--) | Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [getSufficientResolution()](#getSufficientResolution--) | Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, чтобы рисовать черную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, чтобы рисовать черную рамку вокруг каждого слайда. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Получает или задает прозрачный цвет изображения. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Получает или задает прозрачный цвет изображения. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Применяет указанный прозрачный цвет к изображению, если значение равно true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Применяет указанный прозрачный цвет к изображению, если значение равно true. |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. |
| [getIncludeOleData()](#getIncludeOleData--) | True, чтобы преобразовать все данные OLE из презентации в встроенные файлы в результирующий PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, чтобы преобразовать все данные OLE из презентации в встроенные файлы в результирующий PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

По умолчанию [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Возвращаемое значение:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

По умолчанию [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установить true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к уменьшению размера получаемого PDF-документа.

--------------------

Выбор наилучшего коэффициента сжатия изображений требует значительных вычислительных ресурсов и дополнительной оперативной памяти; по умолчанию эта опция отключена.

--------------------

По умолчанию false.

**Возвращаемое значение:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установить true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к уменьшению размера получаемого PDF-документа.

--------------------

Выбор наилучшего коэффициента сжатия изображений требует значительных вычислительных ресурсов и дополнительной оперативной памяти; по умолчанию эта опция отключена.

--------------------

По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True, чтобы встраивать TrueType-шрифты для ASCII-символов 32-127. Шрифты для символов с кодами выше 127 всегда встраиваются. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Возвращаемое значение:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True, чтобы встраивать TrueType-шрифты для ASCII-символов 32-127. Шрифты для символов с кодами выше 127 всегда встраиваются. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию false.

**Возвращаемое значение:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides следует считать общими. Чтение/запись String[].

**Возвращаемое значение:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Возвращает или задает массив пользовательских имен семейств шрифтов, которые Aspose.Slides следует считать общими. Чтение/запись String[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранять его в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в получаемом PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранять его в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в получаемом PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

По умолчанию **false**.

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

Действует только при наличии JPEG-изображений в документе.

Используйте это свойство для получения или задания качества изображений при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — наихудшее качество при максимальном сжатии, а 100 — наилучшее качество при минимальном сжатии.

Значение по умолчанию **100**.

**Возвращаемое значение:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись byte.

--------------------

Действует только при наличии JPEG-изображений в документе.

Используйте это свойство для получения или задания качества изображений при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — наихудшее качество при максимальном сжатии, а 100 — наилучшее качество при минимальном сжатии.

Значение по умолчанию **100**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Желаемый уровень соответствия для генерируемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

По умолчанию [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Возвращаемое значение:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Желаемый уровень соответствия для генерируемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

По умолчанию [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись boolean.

--------------------

По умолчанию **true**. PDF-документ может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng равно true, исходный метафайл конвертируется в формат PNG и сохраняется в PDF как растровое изображение. Если SaveMetafilesAsPng равно false, исходный метафайл конвертируется в векторную графику PDF. Каждый подход имеет свои плюсы и минусы. Например, при конвертации метафайла в PNG может происходить потеря качества при масштабировании полученного документа. При конвертации метафайла в векторную графику PDF могут возникать проблемы с производительностью в средствах просмотра PDF.

**Возвращаемое значение:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись boolean.

--------------------

По умолчанию **true**. PDF-документ может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng равно true, исходный метафайл конвертируется в формат PNG и сохраняется в PDF как растровое изображение. Если SaveMetafilesAsPng равно false, исходный метафайл конвертируется в векторную графику PDF. Каждый подход имеет свои плюсы и минусы. Например, при конвертации метафайла в PNG может происходить потеря качества при масштабировании полученного документа. При конвертации метафайла в векторную графику PDF могут возникать проблемы с производительностью в средствах просмотра PDF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. Чтение/запись float.

Значение: эффект данного параметра зависит от нескольких факторов. Алгоритм пытается подобрать оптимальный размер выходного изображения исходя из значения свойства, размеров исходного изображения и размера кадра изображения. Использование схожих значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображений.

Значение по умолчанию **96**.

**Возвращаемое значение:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. Чтение/запись float.

Значение: эффект данного параметра зависит от нескольких факторов. Алгоритм пытается подобрать оптимальный размер выходного изображения исходя из значения свойства, размеров исходного изображения и размера кадра изображения. Использование схожих значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображений.

Значение по умолчанию **96**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, чтобы рисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, чтобы рисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Получает или задает прозрачный цвет изображения.

Значение: Прозрачный цвет изображения.

**Возвращаемое значение:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Получает или задает прозрачный цвет изображения.

Значение: Прозрачный цвет изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Применяет указанный прозрачный цвет к изображению, если значение равно true.

**Возвращаемое значение:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Применяет указанный прозрачный цвет к изображению, если значение равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True, чтобы преобразовать все данные OLE из презентации в встроенные файлы в результирующий PDF. Чтение/запись boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false** .

**Возвращаемое значение:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True, чтобы преобразовать все данные OLE из презентации в встроенные файлы в результирующий PDF. Чтение/запись boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false** .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |