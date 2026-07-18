---
title: get_BwConversionMode()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Η επιλογή αυτή θα εφαρμοστεί μόνο εάν ITiffOptions::get_CompressionType() είναι ορισμένη σε TiffCompressionTypes::CCITT4 ή TiffCompressionTypes::CCITT3 Read BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /el/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() μέθοδος

Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε εικόνα ασπρόμαυρη. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν [ITiffOptions::get_CompressionType()](../get_compressiontype/) είναι ορισμένη σε [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ή [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Δείτε [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Η προεπιλογή είναι [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε τον αλγόριθμο μετατροπής σε Dithering. ```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## Δείτε επίσης

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)