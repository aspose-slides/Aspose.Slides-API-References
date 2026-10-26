---
title: set_Zip64Mode()
second_title: Aspose.Slides pro C++ API referenci
description: "Určuje, zda je pro dokument Presentation používán formát ZIP64. Výchozí hodnota je Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /cs/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metoda

Určuje, zda je pro dokument [Presentation](../../../aspose.slides/presentation/) používán formát ZIP64. Výchozí hodnota je [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```


## Viz také

* Enum [Zip64Mode](../../zip64mode/)
* Třída [IPptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)