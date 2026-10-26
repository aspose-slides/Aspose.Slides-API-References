---
title: get_Zip64Mode()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica si se utiliza el formato ZIP64 para el documento de Presentación. El valor predeterminado es Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /es/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() método

Especifica si se utiliza el formato ZIP64 para el documento [Presentation](../../../aspose.slides/presentation/). El valor predeterminado es [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## Comentarios

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver también

* Enum [Zip64Mode](../../zip64mode/)
* Clase [IPptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)