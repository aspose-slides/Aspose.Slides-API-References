---
title: get_IncludeOleData()
second_title: Referência da API Aspose.Slides para C++
description: True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura bool.
type: docs
weight: 456
url: /pt/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() método


True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Observações


O padrão é **false**. 

Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Veja também

* Classe [PdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)