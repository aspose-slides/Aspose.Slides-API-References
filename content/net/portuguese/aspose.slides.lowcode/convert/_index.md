---
title: Convert
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um grupo de métodos destinados a converter Presentation../aspose.slides/presentation.
type: docs
weight: 7860
url: /pt/aspose.slides.lowcode/convert/
---
## classe Convert

Representa um grupo de métodos destinados a converter [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Métodos

| Nome | Descrição |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Converte [`Presentation`](../../aspose.slides/presentation) usando a extensão do caminho de saída fornecida para determinar o formato de exportação necessário. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.jpeg", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.jpeg", onde N é o número do slide. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Converte [`Presentation`](../../aspose.slides/presentation) para PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Converte [`Presentation`](../../aspose.slides/presentation) para PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Converte [`Presentation`](../../aspose.slides/presentation) para PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Converte [`Presentation`](../../aspose.slides/presentation) para PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.png", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.png", onde N é o número do slide. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Converte [`Presentation`](../../aspose.slides/presentation) para SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Converte [`Presentation`](../../aspose.slides/presentation) para SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Converte [`Presentation`](../../aspose.slides/presentation) para SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Converte [`Presentation`](../../aspose.slides/presentation) para SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Converte [`Presentation`](../../aspose.slides/presentation) para SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Converte a apresentação de entrada em um conjunto de imagens no formato TIFF. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff", o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.tiff", onde N é o número do slide. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Converte a apresentação de entrada para TIFF com opções personalizadas. Se o nome do arquivo de saída for fornecido como "myPath/myFilename.tiff" e *multipage* for `false`, o resultado será salvo como um conjunto de arquivos "myPath/myFilename_N.tiff", onde N é o número do slide. Caso contrário, se *multipage* for `true`, o resultado será um documento multipágina "myPath/myFilename.tiff". |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback que será invocado para cada [`Slide`](../../aspose.slides/slide), esperando que o caminho de saída seja retornado. |

### Exemplos

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Ver Também

* espaço de nomes [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->