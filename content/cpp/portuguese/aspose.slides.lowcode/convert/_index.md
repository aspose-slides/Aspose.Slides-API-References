---
title: Convert
second_title: Referência da API Aspose.Slides para C++
description: Representa um grupo de métodos destinados a converter Presentation.
type: docs
weight: 27
url: /pt/aspose.slides.lowcode/convert/
---
## Convert classe

Representa um grupo de métodos destinados a converter [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Métodos

| Método | Descrição |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) usando a extensão do caminho de saída fornecida para determinar o formato de exportação necessário. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.jpeg\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.jpeg\", onde N é o número do slide. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.jpeg\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.jpeg\", onde N é o número do slide. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converte a apresentação de entrada em um conjunto de imagens no formato JPEG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.jpeg\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.jpeg\", onde N é o número do slide. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) para PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) para PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) para PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) para PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converte a apresentação de entrada em um conjunto de imagens no formato PNG.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) para SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converte [Presentation](../../aspose.slides/presentation/) para SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converte [Presentation](../../aspose.slides/presentation/) para SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) para SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) para SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte a apresentação de entrada em um conjunto de imagens no formato TIFF.

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.tiff\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.tiff\", onde N é o número do slide. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Converte a apresentação de entrada para o formato TIFF com opções personalizadas. Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.tiff\" e *multipage* for **false**, o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.tiff\", onde N é o número do slide. Caso contrário, se *multipage* for **true**, o resultado será um documento TIFF multipágina \"myPath/myFilename.tiff\". |

## Tipos definidos

| Tipo definido | Descrição |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback que será invocado para cada [Slide](../../aspose.slides/slide/), o caminho de saída esperado a ser retornado. |

## Observações



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Ver também

* Namespace [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)