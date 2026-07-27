---
title: get_Zip64Mode()
second_title: Aspose.Slides para C++ Referencia de API
description: "Especifica si se utiliza el formato ZIP64 para el documento Presentation. El valor predeterminado es Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /es/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() method

Especifica si se utiliza el formato ZIP64 para el documento [Presentation](../../../aspose.slides/presentation/). El valor predeterminado es [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
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

* Enum [Zip64Mode](../../zip64mode/)
* Clase [PptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)