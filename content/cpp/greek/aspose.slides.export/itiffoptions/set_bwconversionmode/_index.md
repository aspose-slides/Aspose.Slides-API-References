---
title: set_BwConversionMode()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν ITiffOptions::get_CompressionType() οριστεί σε TiffCompressionTypes::CCITT4 ή TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode. Η προεπιλογή είναι BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /el/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) μέθοδος

Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν το [ITiffOptions::get_CompressionType()](../get_compressiontype/) οριστεί σε [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) ή [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/). Η προεπιλογή είναι [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
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
* Κλάση [ITiffOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)