---
title: get_BwConversionMode()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ITiffOptions::get_CompressionType() οριστεί σε TiffCompressionTypes::CCITT4 ή TiffCompressionTypes::CCITT3 Διαβάστε BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /el/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() μέθοδος


Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε εικόνα ασπρόμαυρη. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) οριστεί σε [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ή [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Διαβάστε [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Η προεπιλογή είναι [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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

* Απαρίθμηση [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Κλάση [TiffOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)