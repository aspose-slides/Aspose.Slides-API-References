---
title: IPdfOptions
second_title: Справочник API Aspose.Slides для Java
description: Предоставляет параметры, контролирующие способ сохранения презентации в формате PDF.
type: docs
url: /ru/com.aspose.slides/ipdfoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in Pdf format.
## Методы

| Метод | Описание |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [setTextCompression(int value)](#setTextCompression-int-) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True, если необходимо встраивать шрифты TrueType для символов ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True, если необходимо встраивать шрифты TrueType для символов ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Возвращает или задаёт массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Возвращает или задаёт массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Определяет, следует ли встраивать все символы шрифта или только используемую часть. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Определяет, следует ли встраивать все символы шрифта или только используемую часть. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. |
| [getJpegQuality()](#getJpegQuality--) | Возвращает или задаёт значение, определяющее качество JPEG-изображений в документе PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Возвращает или задаёт значение, определяющее качество JPEG-изображений в документе PDF. |
| [getCompliance()](#getCompliance--) | Желаемый уровень соответствия для создаваемого PDF-документа. |
| [setCompliance(int value)](#setCompliance-int-) | Желаемый уровень соответствия для создаваемого PDF-документа. |
| [getPassword()](#getPassword--) | Установка пароля пользователя для защиты PDF-документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установка пароля пользователя для защиты PDF-документа. |
| [getAccessPermissions()](#getAccessPermissions--) | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. |
| [getSufficientResolution()](#getSufficientResolution--) | Возвращает или задаёт значение, определяющее разрешение изображений в документе PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Возвращает или задаёт значение, определяющее разрешение изображений в документе PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, если необходимо отрисовывать чёрную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, если необходимо отрисовывать чёрную рамку вокруг каждого слайда. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задаёт режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Получает или задаёт прозрачный цвет изображения. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Получает или задаёт прозрачный цвет изображения. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Применяет указанный прозрачный цвет к изображению, если true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Применяет указанный прозрачный цвет к изображению, если true. |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. |
| [getIncludeOleData()](#getIncludeOleData--) | True, если необходимо преобразовать все OLE-данные из презентации в встроенные файлы в получаемом PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, если необходимо преобразовать все OLE-данные из презентации в встроенные файлы в получаемом PDF. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Значение по умолчанию: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Возвращает:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Значение по умолчанию: [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

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

Выбор лучшего коэффициента сжатия изображений является вычислительно затратным и требует дополнительного объёма ОЗУ, при этом данная опция по умолчанию имеет значение false.

--------------------

Значение по умолчанию: false.

**Возвращает:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установить true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к уменьшению размера получаемого PDF-документа.

--------------------

Выбор лучшего коэффициента сжатия изображений является вычислительно затратным и требует дополнительного объёма ОЗУ, при этом данная опция по умолчанию имеет значение false.

--------------------

Значение по умолчанию: false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True, если необходимо встраивать шрифты TrueType для символов ASCII 32-127. Шрифты для кодов символов больше 127 всегда встраиваются. Чтение/запись boolean.

--------------------

Значение по умолчанию: **true**.

**Возвращает:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True, если необходимо встраивать шрифты TrueType для символов ASCII 32-127. Шрифты для кодов символов больше 127 всегда встраиваются. Чтение/запись boolean.

--------------------

Значение по умолчанию: **true**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. Значение по умолчанию: false.

**Возвращает:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. Значение по умолчанию: false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Возвращает или задаёт массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/запись String[].

**Возвращает:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Возвращает или задаёт массив пользовательских имен семейств шрифтов, которые Aspose.Slides должен считать общими. Чтение/запись String[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Определяет, следует ли встраивать все символы шрифта или только используемую часть. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Возвращает:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Определяет, следует ли встраивать все символы шрифта или только используемую часть. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может повысить качество текста в результирующем PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Возвращает:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может повысить качество текста в результирующем PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Возвращает или задаёт значение, определяющее качество JPEG-изображений в документе PDF. Чтение/запись byte.

--------------------

Действует только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений в документе при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — худшее качество с максимальным сжатием, а 100 — лучшее качество с минимальным сжатием.

Значение по умолчанию: **100**.

**Возвращает:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Возвращает или задаёт значение, определяющее качество JPEG-изображений в документе PDF. Чтение/запись byte.

--------------------

Действует только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений в документе при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — худшее качество с максимальным сжатием, а 100 — лучшее качество с минимальным сжатием.

Значение по умолчанию: **100**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Значение по умолчанию: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Возвращает:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Значение по умолчанию: [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Установка пароля пользователя для защиты PDF-документа. Чтение/запись String.

**Возвращает:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Установка пароля пользователя для защиты PDF-документа. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. Смотрите [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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


**Возвращает:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. Смотрите [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

True, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись boolean.

--------------------

Значение по умолчанию: **true**. Pdf документ может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng имеет значение true, исходный метафайл преобразуется в формат PNG и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng имеет значение false, исходный метафайл преобразуется в векторную графику Pdf. Каждый подход имеет свои преимущества и недостатки. Например, при преобразовании метафайла в PNG возможна небольшая потеря качества при масштабировании получаемого документа. При преобразовании метафайла в векторную графику Pdf могут возникать проблемы с производительностью в средствах просмотра Pdf.

**Возвращает:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True, если необходимо преобразовать все метафайлы, используемые в презентации, в PNG-изображения. Чтение/запись boolean.

--------------------

Значение по умолчанию: **true**. Pdf документ может содержать векторную графику и растровые изображения. Если SaveMetafilesAsPng имеет значение true, исходный метафайл преобразуется в формат PNG и сохраняется в Pdf как растровое изображение. Если SaveMetafilesAsPng имеет значение false, исходный метафайл преобразуется в векторную графику Pdf. Каждый подход имеет свои преимущества и недостатки. Например, при преобразовании метафайла в PNG возможна небольшая потеря качества при масштабировании получаемого документа. При преобразовании метафайла в векторную графику Pdf могут возникать проблемы с производительностью в средствах просмотра Pdf.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Возвращает или задаёт значение, определяющее разрешение изображений в документе PDF. Чтение/запись float.

Значение: Эффект этого параметра зависит от нескольких факторов. Алгоритм пытается получить лучший размер выходного изображения в соответствии со значением свойства, размером исходного изображения и размером кадра изображения. Использование аналогичных значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображения.

Значение по умолчанию: **96**.

**Возвращает:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Возвращает или задаёт значение, определяющее разрешение изображений в документе PDF. Чтение/запись float.

Значение: Эффект этого параметра зависит от нескольких факторов. Алгоритм пытается получить лучший размер выходного изображения в соответствии со значением свойства, размером исходного изображения и размером кадра изображения. Использование аналогичных значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображения.

Значение по умолчанию: **96**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True, если необходимо отрисовывать чёрную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Возвращает:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True, если необходимо отрисовывать чёрную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

Значение по умолчанию: **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Получает или задаёт режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Возвращает:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Получает или задаёт режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Color getImageTransparentColor()
```

Получает или задаёт прозрачный цвет изображения.

Значение: Цвет прозрачного изображения.

**Возвращает:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

Получает или задаёт прозрачный цвет изображения.

Значение: Цвет прозрачного изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Применяет указанный прозрачный цвет к изображению, если true.

**Возвращает:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Применяет указанный прозрачный цвет к изображению, если true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращает:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True, если необходимо преобразовать все OLE-данные из презентации в встроенные файлы в получаемом PDF. Чтение/запись  boolean .

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

Значение по умолчанию:  **false** .

**Возвращает:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

True, если необходимо преобразовать все OLE-данные из презентации в встроенные файлы в получаемом PDF. Чтение/запись  boolean .

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

Значение по умолчанию:  **false** .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |