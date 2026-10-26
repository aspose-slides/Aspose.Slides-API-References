---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API referencia
description: "Megadja a prezentációs dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték a CompressionLevel::Level6."
type: docs
weight: 79
url: /hu/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() metódus

Megadja a prezentációs dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Megjegyzések

A magasabb tömörítési szintek kisebb fájlokat eredményeznek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.  

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Enum [CompressionLevel](../../compressionlevel/)
* Osztály [PptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)