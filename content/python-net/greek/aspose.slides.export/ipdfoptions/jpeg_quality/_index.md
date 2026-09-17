---
title: jpeg_quality property
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality ιδιότητα
Returns or sets a value determining the quality of the JPEG images inside PDF document.
            Ανάγνωση/εγγραφή **int**.

### Παρατηρήσεις

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format.
            The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100** .

### Ορισμός:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`IPdfOptions`](/slides/python-net/el/aspose.slides.export/ipdfoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)