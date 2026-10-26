---
title: get_IncludeOleData()
second_title: Riferimento API di Aspose.Slides per C++
description: True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. Read bool.
type: docs
weight: 456
url: /it/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metodo

True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. Read **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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