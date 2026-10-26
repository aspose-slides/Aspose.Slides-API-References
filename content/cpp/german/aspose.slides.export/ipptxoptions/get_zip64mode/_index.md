---
title: get_Zip64Mode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /de/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() Methode


Gibt an, ob das ZIP64-Format für das [Presentation](../../../aspose.slides/presentation/) Dokument verwendet wird. Der Standardwert ist [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## Anmerkungen


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```




## Siehe auch

* Enum [Zip64Mode](../../zip64mode/)
* Klasse [IPptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)