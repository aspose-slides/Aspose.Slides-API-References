---
title: set_Zip64Mode()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica se o formato ZIP64 é usado para o documento Presentation. O valor padrão é Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /pt/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) método


Especifica se o formato ZIP64 é usado para o documento [Presentation](../../../aspose.slides/presentation/). O valor padrão é [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Observações


Exemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Veja Também

* Enum [Zip64Mode](../../zip64mode/)
* classe [IPptxOptions](../)
* namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)