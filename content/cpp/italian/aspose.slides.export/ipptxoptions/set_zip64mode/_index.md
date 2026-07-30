---
title: set_Zip64Mode()
second_title: Aspose.Slides per C++ Riferimento API
description: "Specifica se il formato ZIP64 è usato per il documento Presentation. Il valore predefinito è Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /it/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metodo



Specifica se il formato ZIP64 è utilizzato per il documento [Presentation](../../../aspose.slides/presentation/). Il valore predefinito è [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Note


Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Vedi anche

* Enum [Zip64Mode](../../zip64mode/)
* Classe [IPptxOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)