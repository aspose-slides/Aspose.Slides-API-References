---
title: set_Zip64Mode()
second_title: Aspose.Slides C++ API referenciája
description: "Megadja, hogy a ZIP64 formátum használatos-e a Presentation dokumentumban. Az alapértelmezett érték a Zip64Mode::IfNecessary."
type: docs
weight: 40
url: /hu/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) method


Megadja, hogy a ZIP64 formátum használatos-e a [Presentation](../../../aspose.slides/presentation/) dokumentumban. Az alapértelmezett érték [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Lásd még

* Felsoroló [Zip64Mode](../../zip64mode/)
* Osztály [IPptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)