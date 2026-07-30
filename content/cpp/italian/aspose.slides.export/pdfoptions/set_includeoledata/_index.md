---
title: set_IncludeOleData()
second_title: Riferimento API Aspose.Slides per C++
description: True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi bool.
type: docs
weight: 469
url: /it/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metodo


True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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

* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)