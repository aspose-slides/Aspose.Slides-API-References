---
title: ToPng()
second_title: Referência da API Aspose.Slides para C++
description: Converte a apresentação de entrada em um conjunto de imagens no formato PNG.  Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide.
type: docs
weight: 53
url: /pt/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) método


Converte a apresentação de entrada em um conjunto de imagens no formato PNG. 

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída. |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) método


Converte a apresentação de entrada em um conjunto de imagens no formato PNG. 

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A apresentação de entrada |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | O tamanho de cada imagem gerada. |
## Observações 




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) método


Converte a apresentação de entrada em um conjunto de imagens no formato PNG. 

 Se o nome do arquivo de saída for fornecido como \"myPath/myFilename.png\", o resultado será salvo como um conjunto de arquivos \"myPath/myFilename_N.png\", onde N é o número do slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A apresentação de entrada. |
| outputFileName | [System::String](../../../system/string/) | O nome do arquivo de saída. |
| scale | **float** | O fator de escala aplicado às imagens de saída em relação ao tamanho original do slide. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | As opções de renderização. |
## Observações 




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)