---
title: Convert
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de métodos destinados a converter .
type: docs
url: /pt/com.aspose.slides/convert/
---
**Herança:**
java.lang.Object
```
public class Convert
```

Representa um grupo de métodos destinados a converter [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Convert()](#Convert--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) usando a extensão do caminho de saída fornecida para determinar o formato de exportação necessário. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) para PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) para PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) para PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) para PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) para SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Converte [Presentation](../../com.aspose.slides/presentation) para SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Converte [Presentation](../../com.aspose.slides/presentation) para SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) para SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) para SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Converte a apresentação de entrada em um conjunto de imagens no formato TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Converte a apresentação de entrada para o formato TIFF com opções personalizadas. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) usando a extensão do caminho de saída fornecida para determinar o formato de exportação necessário.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | java.lang.String | Caminho da apresentação de entrada |
| outPath | java.lang.String | Caminho de saída |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) para PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | java.lang.String | Caminho da apresentação de entrada |
| outPath | java.lang.String | Caminho de saída |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) para PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | java.lang.String | Caminho da apresentação de entrada |
| outPath | java.lang.String | Caminho de saída |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opções de saída PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) para PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação de entrada |
| outPath | java.lang.String | Caminho de saída |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) para PDF.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação de entrada |
| outPath | java.lang.String | Caminho de saída |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opções de saída PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) para SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | java.lang.String | Caminho da apresentação de entrada |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) para SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | java.lang.String | Caminho da apresentação de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que retorna o caminho de saída SVG para cada slide na apresentação |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) para SVG.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que retorna o caminho de saída SVG para cada slide na apresentação |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) para SVG.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação de entrada |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de exportação SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) para SVG.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Apresentação de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que retorna o caminho de saída SVG para cada slide na apresentação |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opções de exportação SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada |
| outputFileName | java.lang.String | O nome do arquivo de saída. |
| imageSize | [Size](../../com.aspose.slides.android/size) | O tamanho de cada imagem gerada. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |
| scale | float | O fator de escala aplicado às imagens de saída em relação ao tamanho original do slide. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | As opções de renderização. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada |
| outputFileName | java.lang.String | O nome do arquivo de saída. |
| imageSize | [Size](../../com.aspose.slides.android/size) | O tamanho de cada imagem gerada. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |
| scale | float | O fator de escala aplicado às imagens de saída em relação ao tamanho original do slide. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | As opções de renderização. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Converte a apresentação de entrada em um conjunto de imagens no formato TIFF. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.tiff", onde N é o número do slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Converte a apresentação de entrada para o formato TIFF com opções personalizadas. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff" e multipage for false, o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.tiff", onde N é o número do slide. Caso contrário, se multipage for true, o resultado será um documento TIFF de várias páginas "myPath/myFilename.tiff".

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A apresentação de entrada. |
| outputFileName | java.lang.String | O nome do arquivo de saída. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | As opções de salvamento TIFF. |
| multipage | boolean | Especifica se o documento TIFF gerado deve ser de várias páginas. |