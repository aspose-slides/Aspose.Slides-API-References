---
title: PdfOptions
second_title: Справочник API Aspose.Slides для Java
description: Предоставляет параметры, контролирующие сохранение презентации в формате PDF.
type: docs
url: /ru/com.aspose.slides/pdfoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Предоставляет параметры, которые контролируют, как презентация сохраняется в формате PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Создает экземпляр класса PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Устанавливает качество JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Устанавливает поведение для метафайлов
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Устанавливает уровень сжатия текста
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Определяет стандарт PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Сохраняет презентацию в формате PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Создает объект класса Presentation, представляющий файл PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Создает экземпляр класса PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Добавляет скрытые слайды
>      pdfOptions.setShowHiddenSlides(true);
>      // Сохраняет презентацию в формате PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Создает объект Presentation, представляющий файл PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Создает экземпляр класса PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Устанавливает пароль PDF и разрешения доступа
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Сохраняет презентацию в формате PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Создает объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Установка типа и размера слайда
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Конструктор по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортируемом документе. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Указывает, следует ли включать скрытые слайды в сгенерированный документ. |
| [getTextCompression()](#getTextCompression--) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [setTextCompression(int value)](#setTextCompression-int-) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Указывает, должен ли автоматически выбираться наиболее эффективный тип сжатия (вместо используемого по умолчанию) для каждого изображения. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Указывает, должен ли автоматически выбираться наиболее эффективный тип сжатия (вместо используемого по умолчанию) для каждого изображения. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Определяет, будет ли Aspose.Slides встраивать обычные шрифты для текста ASCII (диапазон кодов 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Определяет, будет ли Aspose.Slides встраивать обычные шрифты для текста ASCII (диапазон кодов 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Возвращает или задает массив пользовательских названий семейств шрифтов, которые Aspose.Slides должен рассматривать как обычные. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Возвращает или задает массив пользовательских названий семейств шрифтов, которые Aspose.Slides должен рассматривать как обычные. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Определяет, следует ли встраивать все символы шрифта или только используемое подмножество. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. |
| [getJpegQuality()](#getJpegQuality--) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. |
| [getCompliance()](#getCompliance--) | Желаемый уровень соответствия для создаваемого PDF-документа. |
| [setCompliance(int value)](#setCompliance-int-) | Желаемый уровень соответствия для создаваемого PDF-документа. |
| [getPassword()](#getPassword--) | Установка пользовательского пароля для защиты PDF-документа. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установка пользовательского пароля для защиты PDF-документа. |
| [getAccessPermissions()](#getAccessPermissions--) | Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, чтобы нарисовать черную рамку вокруг каждого слайда. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, чтобы нарисовать черную рамку вокруг каждого слайда. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Получает или задает прозрачный цвет изображения. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Получает или задает прозрачный цвет изображения. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Применяет указанный прозрачный цвет к изображению, если true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Применяет указанный прозрачный цвет к изображению, если true. |
| [getIncludeOleData()](#getIncludeOleData--) | True, чтобы преобразовать все OLE-данные из презентации во вложенные файлы в получаемом PDF. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True, чтобы преобразовать все OLE-данные из презентации во вложенные файлы в получаемом PDF. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Конструктор по умолчанию.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортируемом документе. Только для чтения [IInkOptions](../../com.aspose.slides/iinkoptions)

**Возвращаемое значение:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Возвращаемое значение:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Указывает тип сжатия, используемый для всего текстового содержимого в документе. Чтение/запись [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

По умолчанию [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Возвращаемое значение:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
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
public final boolean getBestImagesCompressionRatio()
```

Указывает, должен ли автоматически выбираться наиболее эффективный тип сжатия (вместо используемого по умолчанию) для каждого изображения. Если установить true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа.

--------------------

Выбор лучшего коэффициента сжатия изображений требует значительных вычислительных ресурсов и дополнительной оперативной памяти, и по умолчанию отключён.

--------------------

По умолчанию false.

**Возвращаемое значение:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Указывает, должен ли автоматически выбираться наиболее эффективный тип сжатия (вместо используемого по умолчанию) для каждого изображения. Если установить true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа.

--------------------

Выбор лучшего коэффициента сжатия изображений требует значительных вычислительных ресурсов и дополнительной оперативной памяти, и по умолчанию отключён.

--------------------

По умолчанию false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Определяет, будет ли Aspose.Slides встраивать обычные шрифты для текста ASCII (диапазон кодов 33..127). Шрифты для кодов выше 127 всегда встраиваются. Список обычных шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Возвращаемое значение:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Определяет, будет ли Aspose.Slides встраивать обычные шрифты для текста ASCII (диапазон кодов 33..127). Шрифты для кодов выше 127 всегда встраиваются. Список обычных шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты. Чтение/запись boolean.

--------------------

По умолчанию **true**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Возвращает или задает массив пользовательских названий семейств шрифтов, которые Aspose.Slides должен рассматривать как обычные. Чтение/запись String[].

**Возвращаемое значение:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Возвращает или задает массив пользовательских названий семейств шрифтов, которые Aspose.Slides должен рассматривать как обычные. Чтение/запись String[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Определяет, должны ли встраиваться все символы шрифта или только используемое подмножество. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Определяет, должны ли встраиваться все символы шрифта или только используемое подмножество. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в получаемом PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Указывает, следует ли растеризовать текст в виде растрового изображения и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в получаемом PDF для некоторых шрифтов. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись byte.

--------------------

Действует только при наличии JPEG-изображений в документе.

Используйте это свойство для получения или установки качества изображений при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — наихудшее качество при максимальном сжатии, а 100 — лучшее качество при минимальном сжатии.

Значение по умолчанию **100**.

**Возвращаемое значение:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа. Чтение/запись byte.

--------------------

Действует только при наличии JPEG-изображений в документе.

Используйте это свойство для получения или установки качества изображений при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 — наихудшее качество при максимальном сжатии, а 100 — лучшее качество при минимальном сжатии.

Значение по умолчанию **100**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

По умолчанию [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Возвращаемое значение:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Желаемый уровень соответствия для создаваемого PDF-документа. Чтение/запись [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

По умолчанию [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Установка пользовательского пароля для защиты PDF-документа. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем. См. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```

Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа пользователем. См. [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final boolean getSaveMetafilesAsPng()
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Чтение/запись boolean.

--------------------

По умолчанию **true**. PDF-документ может содержать векторную графику и растр. Если SaveMetafilesAsPng установлено в true, исходный метафайл преобразуется в формат PNG и сохраняется в PDF как растровое изображение. Если SaveMetafilesAsPng установлено в false, исходный метафайл преобразуется в векторную графику PDF. Каждый подход имеет свои преимущества и недостатки. Например, при конвертации метафайла в PNG возможна потеря качества при масштабировании результирующего документа. При конвертации метафайла в векторную графику PDF могут возникнуть проблемы производительности в среде просмотра PDF.

**Возвращаемое значение:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Чтение/запись boolean.

--------------------

По умолчанию **true**. PDF-документ может содержать векторную графику и растр. Если SaveMetafilesAsPng установлено в true, исходный метафайл преобразуется в формат PNG и сохраняется в PDF как растровое изображение. Если SaveMetafilesAsPng установлено в false, исходный метафайл преобразуется в векторную графику PDF. Каждый подход имеет свои преимущества и недостатки. Например, при конвертации метафайла в PNG возможна потеря качества при масштабировании результирующего документа. При конвертации метафайла в векторную графику PDF могут возникнуть проблемы производительности в среде просмотра PDF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. Чтение/запись float.

Значение: Эффект параметра зависит от нескольких факторов. Алгоритм пытается получить наилучший размер выходного изображения в зависимости от значения свойства, размера исходного изображения и размера кадра изображения. Использование схожих значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображения.

Значение по умолчанию **96**.

**Возвращаемое значение:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Возвращает или задает значение, определяющее разрешение изображений внутри PDF-документа. Чтение/запись float.

Значение: Эффект параметра зависит от нескольких факторов. Алгоритм пытается получить наилучший размер выходного изображения в зависимости от значения свойства, размера исходного изображения и размера кадра изображения. Использование схожих значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для получения заметного эффекта.

--------------------

Свойство влияет на размер файла, время экспорта и качество изображения.

Значение по умолчанию **96**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, чтобы нарисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, чтобы нарисовать черную рамку вокруг каждого слайда. Чтение/запись boolean.

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Получает или задает прозрачный цвет изображения.

Значение: Прозрачный цвет изображения.

**Возвращаемое значение:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Получает или задает прозрачный цвет изображения.

Значение: Прозрачный цвет изображения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Применяет указанный прозрачный цвет к изображению, если true.

**Возвращаемое значение:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Применяет указанный прозрачный цвет к изображению, если true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

True, чтобы преобразовать все OLE-данные из презентации во вложенные файлы в получаемом PDF. Чтение/запись boolean.

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

По умолчанию **false**.

**Возвращаемое значение:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

True, чтобы преобразовать все OLE-данные из презентации во вложенные файлы в получаемом PDF. Чтение/запись boolean.

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

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |