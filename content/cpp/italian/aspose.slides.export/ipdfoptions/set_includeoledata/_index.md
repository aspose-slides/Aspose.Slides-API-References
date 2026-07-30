---
title: set_IncludeOleData()
second_title: Riferimento API di Aspose.Slides per C++
description: True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi bool.
type: docs
weight: 469
url: /it/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) metodo

True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* Classe [IPdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)