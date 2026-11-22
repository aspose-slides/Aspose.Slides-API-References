---
title: compress_presentation method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Reduces the size of a presentation by applying all available compression steps:
            
* Καταργεί τις αχρησιμοποίητες κύριες διαφάνειες **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Καταργεί τις αχρησιμοποίητες διαφάνειες διάταξης **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Διατηρεί μόνο τα σύμβολα που χρησιμοποιούνται στην ενσωματωμένη γραμματοσειρά **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Μειώνει την ανάλυση των εικόνων σε 150 DPI και διαγράφει τις περικομμένες περιοχές των εικόνων **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/el/aspose.slides/presentation) | Η παρουσίαση προς συμπίεση. |

### Παρατηρήσεις
Για να προσαρμόσετε τη συμπίεση, για παράδειγμα ώστε να χρησιμοποιήσετε διαφορετική ανάλυση εικόνας ή να παραλείψετε ένα βήμα,
            καλέστε τις παραπάνω μεθόδους ξεχωριστά αντί για αυτήν.
            Οι περικομμένες περιοχές των εικόνων διαγράφονται μόνιμα και δεν μπορούν να επαναφερθούν στο PowerPoint.

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` είναι `None`. |



### Δείτε επίσης
* κλάση [`Compress`](/slides/python-net/el/aspose.slides.lowcode/compress)
* κλάση [`Presentation`](/slides/python-net/el/aspose.slides/presentation)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)