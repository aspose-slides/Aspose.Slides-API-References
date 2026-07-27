---
title: set_Zip64Mode()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica si se utiliza el formato ZIP64 para el documento Presentation. El valor predeterminado es Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /es/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) método

Especifica si se utiliza el formato ZIP64 para el documento [Presentation](../../../aspose.slides/presentation/). El valor predeterminado es [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver también

* Enumeración [Zip64Mode](../../zip64mode/)
* Clase [PptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)