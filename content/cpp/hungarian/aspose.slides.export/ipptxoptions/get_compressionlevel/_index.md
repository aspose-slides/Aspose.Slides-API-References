---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API-referencia
description: "Megadja a bemutató dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték a CompressionLevel::Level6."
type: docs
weight: 79
url: /hu/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() metódus


Meghatározza a tömörítési szintet, amelyet a bemutató dokumentum mentésekor használnak. Az alapértelmezett érték [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Megjegyzések


A magasabb tömörítési szintek kisebb fájlokhoz vezetnek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a bemutató tartalmától függ. 

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Enum [CompressionLevel](../../compressionlevel/)
* Osztály [IPptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)