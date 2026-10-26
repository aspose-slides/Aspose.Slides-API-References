---
title: set_IncludeOleData()
second_title: Referência da API Aspose.Slides para C++
description: True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Escreve **bool**.
type: docs
weight: 469
url: /pt/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) método

True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Escreve **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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

## Veja Também

* Classe [PdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)