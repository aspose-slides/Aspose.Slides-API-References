---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κάνει συμπίεση του Presentation αφαιρώντας μη χρησιμοποιημένες κύριες διαφάνειες.
type: docs
weight: 1
url: /el/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) μέθοδος

Κάνει συμπίεση του [Presentation](../../../aspose.slides/presentation/) αφαιρώντας μη χρησιμοποιημένες κύριες διαφάνειες.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Η παρουσίαση |
## Σχόλια

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)