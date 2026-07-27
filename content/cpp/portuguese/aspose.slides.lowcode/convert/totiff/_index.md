---
title: ToTiff()
second_title: Referência da API Aspose.Slides para C++
description: Converte a apresentação de entrada em um conjunto de imagens no formato TIFF. Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.tiff\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.tiff\", onde N é o número do slide.
type: docs
weight: 66
url: /pt/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) método


Converte a apresentação de entrada em um conjunto de imagens no formato TIFF. 

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.tiff\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.tiff\", onde N é o número do slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída. |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) método


Converte a apresentação de entrada para o formato TIFF com opções personalizadas. Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.tiff\" e *multipage* for **false**, o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.tiff\", onde N é o número do slide. Caso contrário, se *multipage* for **true**, o resultado será um documento de múltiplas páginas \"myPath/myFilename.tiff\".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | As opções de salvamento TIFF. |
| multipage | **bool** | Especifica se o documento TIFF gerado deve ser de múltiplas páginas. |
## Observações




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)