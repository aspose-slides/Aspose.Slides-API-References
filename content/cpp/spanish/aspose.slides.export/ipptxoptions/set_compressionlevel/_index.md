---
title: set_CompressionLevel()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica el nivel de compresión usado al guardar el documento de presentación. El valor predeterminado es CompressionLevel::Level6."
type: docs
weight: 92
url: /es/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) método

Especifica el nivel de compresión usado al guardar el documento de presentación. El valor predeterminado es [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Observaciones

Los niveles de compresión más altos generan archivos más pequeños pero requieren más tiempo de procesamiento. La relación de compresión real depende del contenido de la presentación. 

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Ver también

* Enumeración [CompressionLevel](../../compressionlevel/)
* Clase [IPptxOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)