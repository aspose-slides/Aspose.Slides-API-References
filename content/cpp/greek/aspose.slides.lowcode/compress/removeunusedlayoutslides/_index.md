---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides για C++ Αναφορά API
description: Πραγματοποιεί τη συμπίεση της Presentation αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης.
type: docs
weight: 14
url: /el/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) μέθοδος

Πραγματοποιεί συμπίεση του [Presentation](../../../aspose.slides/presentation/) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Το στιγμιότυπο παρουσίασης |
## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [Compress](../)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)