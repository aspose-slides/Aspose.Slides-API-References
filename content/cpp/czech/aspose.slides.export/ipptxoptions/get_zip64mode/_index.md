---
title: get_Zip64Mode()
second_title: Aspose.Slides pro C++ API Reference
description: "Určuje, zda je pro dokument Presentation používán formát ZIP64. Výchozí hodnota je Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /cs/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() metoda

Určuje, zda je pro dokument [Presentation](../../../aspose.slides/presentation/) používán formát ZIP64. Výchozí hodnota je [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
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

* Výčet [Zip64Mode](../../zip64mode/)
* Třída [IPptxOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)