---
title: get_Zip64Mode()
second_title: Aspose.Slides C++ API referencia
description: "Megadja, hogy a ZIP64 formátum használatos-e a Presentation dokumentumban. Az alapértelmezett érték a Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /hu/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() metódus


Megadja, hogy a ZIP64 formátum használatos-e a [Presentation](../../../aspose.slides/presentation/) dokumentumban. Az alapértelmezett érték [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
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

* Enum [Zip64Mode](../../zip64mode/)
* Osztály [IPptxOptions](../)
* Névterület [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)