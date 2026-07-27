---
title: get_Zip64Mode()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica se o formato ZIP64 é usado para o documento Presentation. O valor padrão é Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /pt/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() método


Especifica se o formato ZIP64 é usado para o [Presentation](../../../aspose.slides/presentation/) documento. O valor padrão é [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
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
* Classe [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)