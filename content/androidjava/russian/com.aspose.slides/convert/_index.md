---
title: Convert
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет группу методов, предназначенных для преобразования .
type: docs
url: /ru/com.aspose.slides/convert/
--- **Наследование:**  
java.lang.Object  
```
public class Convert
```

Представляет группу методов, предназначенных для преобразования [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Convert()](#Convert--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) с использованием расширения выходного пути для определения требуемого формата экспорта. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Конвертирует входную презентацию в набор изображений формата JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Конвертирует входную презентацию в набор изображений формата JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Конвертирует входную презентацию в набор изображений формата JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Конвертирует входную презентацию в набор изображений формата PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Конвертирует входную презентацию в набор изображений формата PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Конвертирует входную презентацию в набор изображений формата PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Конвертирует входную презентацию в набор изображений формата TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Конвертирует входную презентацию в формат TIFF с пользовательскими параметрами. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) с использованием расширения выходного пути для определения требуемого формата экспорта.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | java.lang.String | Путь к входной презентации |
| outPath | java.lang.String | Путь к выходному файлу |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | java.lang.String | Путь к входной презентации |
| outPath | java.lang.String | Путь к выходному файлу |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | java.lang.String | Путь к входной презентации |
| outPath | java.lang.String | Путь к выходному файлу |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Параметры вывода PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| outPath | java.lang.String | Путь к выходному файлу |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| outPath | java.lang.String | Путь к выходному файлу |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Параметры вывода PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | java.lang.String | Путь к входной презентации |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | java.lang.String | Путь к входной презентации |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Обратный вызов, возвращающий путь вывода SVG для каждого слайда презентации |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Обратный вызов, возвращающий путь вывода SVG для каждого слайда презентации |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры экспорта SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Конвертирует [Presentation](../../com.aspose.slides/presentation) в SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      }, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Обратный вызов, возвращающий путь вывода SVG для каждого слайда презентации |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры экспорта SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Конвертирует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```


Конвертирует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| outputFileName | java.lang.String | Имя выходного файла. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер каждого создаваемого изображения. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Конвертирует входную презентацию в набор изображений формата JPEG. Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |
| scale | float | Коэффициент масштабирования, применяемый к изображениями относительно оригинального размера слайда. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Конвертирует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```


Конвертирует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация |
| outputFileName | java.lang.String | Имя выходного файла. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер каждого создаваемого изображения. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Конвертирует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N => номер слайда.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |
| scale | float | Коэффициент масштабирования, применяемый к изображениям относительно оригинального размера слайда. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Конвертирует входную презентацию в набор изображений формата TIFF. Если имя выходного файла указано как "myPath/myFilename.tiff", результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Конвертирует входную презентацию в формат TIFF с пользовательскими параметрами. Если имя выходного файла указано как "myPath/myFilename.tiff" и multipage равно false, результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда. Если же multipage равно true, результат будет представлять собой многостраничный документ "myPath/myFilename.tiff".

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Входная презентация. |
| outputFileName | java.lang.String | Имя выходного файла. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Параметры сохранения TIFF. |
| multipage | boolean | Указывает, должен ли сформированный документ TIFF быть многостраничным. |