---
title: set_BwConversionMode()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ITiffOptions::get_CompressionType() είναι ορισμένο σε TiffCompressionTypes::CCITT4 ή TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode::Default."
type: docs
weight: 209
url: /el/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) μέθοδος

Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) είναι ορισμένο σε [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ή [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Η προεπιλογή είναι [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε τον αλγόριθμο μετατροπής σε Dithering. 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Δείτε επίσης

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Κλάση [TiffOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)