---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Κάνει συμπίεση της Presentation αφαιρώντας αχρησιμοποίητους χαρακτήρες από ενσωματωμένες γραμματοσειρές.
type: docs
weight: 27
url: /el/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) μέθοδος

Κάνει συμπίεση του [Presentation](../../../aspose.slides/presentation/) αφαιρώντας αχρησιμοποίητους χαρακτήρες από ενσωματωμένες γραμματοσειρές.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Το αντικείμενο παρουσίασης |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [Compress](../)
* Ονομαχώρος [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)