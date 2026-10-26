---
title: get_IncludeOleData()
second_title: Aspose.Slides per C++ Riferimento API
description: True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura bool.
type: docs
weight: 456
url: /it/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metodo


True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Osservazioni


Il valore predefinito è **false**. 

Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Vedi anche

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)