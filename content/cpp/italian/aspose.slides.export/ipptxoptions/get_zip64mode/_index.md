---
title: get_Zip64Mode()
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica se il formato ZIP64 è usato per il documento di Presentazione. Il valore predefinito è Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /it/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() metodo


Specifica se il formato ZIP64 è usato per il documento [Presentation](../../../aspose.slides/presentation/).
Il valore predefinito è [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Vedi anche

* Enumerazione [Zip64Mode](../../zip64mode/)
* Classe [IPptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)