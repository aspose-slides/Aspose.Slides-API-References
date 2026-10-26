---
title: set_CompressionLevel()
second_title: Aspose.Slides C++ API Referencia
description: "Megadja a prezentációs dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték a CompressionLevel::Level6."
type: docs
weight: 92
url: /hu/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) metódus


Megadja a prezentációs dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
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
* Osztály [IPptxOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)