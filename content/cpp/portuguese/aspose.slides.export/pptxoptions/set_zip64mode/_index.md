---
title: set_Zip64Mode()
second_title: Aspose.Slides para C++ Referência da API
description: "Especifica se o formato ZIP64 é usado para o documento Presentation. O valor padrão é Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /pt/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) método

Especifica se o formato ZIP64 é usado para o documento [Presentation](../../../aspose.slides/presentation/). O valor padrão é [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
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
* Espaço de nomes [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)