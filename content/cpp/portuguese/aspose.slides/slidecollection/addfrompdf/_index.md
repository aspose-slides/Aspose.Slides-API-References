---
title: AddFromPdf()
second_title: Referência da API Aspose.Slides for C++
description: Cria slides a partir do documento PDF e os adiciona ao final da coleção.
type: docs
weight: 183
url: /pt/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) método


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Um caminho para o documento PDF |

### Valor de Retorno

Slides adicionados
## Observações



Exemplo: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) método


Cria slides a partir do documento PDF e os adiciona ao final da coleção considerando as opções de importação de PDF.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Um caminho para o documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opções de importação de PDF |

### Valor de Retorno

Slides adicionados
## Observações



Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) método


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um stream que será usado como fonte do documento PDF |

### Valor de Retorno

Slides adicionados
## Observações



Exemplo: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) método


Cria slides a partir do documento PDF e os adiciona ao final da coleção.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um stream que será usado como fonte do documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opções de importação de PDF |

### Valor de Retorno

Slides adicionados
## Observações



Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// definir detecção de tabelas
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [SlideCollection](../)
* Classe [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)