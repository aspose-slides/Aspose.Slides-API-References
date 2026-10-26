---
title: get_Zip64Mode()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica se il formato ZIP64 viene utilizzato per il documento Presentation. Il valore predefinito è Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /it/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() metodo


Specifica se il formato ZIP64 viene utilizzato per il documento [Presentation](../../../aspose.slides/presentation/). Il valore predefinito è [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
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

* Enum [Zip64Mode](../../zip64mode/)
* Classe [PptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)