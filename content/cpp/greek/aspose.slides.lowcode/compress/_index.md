---
title: Compress
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεί μια ομάδα μεθόδων που προορίζονται για τη συμπίεση του Presentation.
type: docs
weight: 14
url: /el/aspose.slides.lowcode/compress/
---
## Κλάση Compress


Αντιπροσωπεί μια ομάδα μεθόδων που προορίζονται για τη συμπίεση του [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Πραγματοποιεί τη συμπίεση του [Presentation](../../aspose.slides/presentation/) αφαιρώντας αχρησιμοποίητους χαρακτήρες από ενσωματωμένες γραμματοσειρές. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Πραγματοποιεί τη συμπίεση του [Presentation](../../aspose.slides/presentation/) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Πραγματοποιεί τη συμπίεση του [Presentation](../../aspose.slides/presentation/) αφαιρώντας αχρησιμοποίητες κύριες διαφάνειες. |
## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::LowCode](../)
* Βιβλιοθήκη [Aspose.Slides](../../)