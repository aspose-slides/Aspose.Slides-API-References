---
title: get_IncludeOleData()
second_title: Referência da API Aspose.Slides para C++
description: Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Ler bool.
type: docs
weight: 456
url: /pt/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() método

Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Ler **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

## Ver também

* Classe [IPdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)