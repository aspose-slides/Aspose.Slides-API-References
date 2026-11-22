---
title: compress_images method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Μειώνει την ανάλυση των εικόνων στην παρουσίαση και διαγράφει τις περικομμένες περιοχές τους,
            παρόμοια με το PowerPoint's "Compress Pictures" που εφαρμόζεται σε όλες τις εικόνες.
            Επεξεργάζονται εικόνες στις διαφάνειες, στις διαφάνειες διάταξης και στις κύριες διαφάνειες, συμπεριλαμβανομένων των εικόνων μέσα σε ομαδοποιημένα σχήματα
            και γεμίσματα εικόνας των σχημάτων.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) | Η παρουσίαση προς επεξεργασία. |
| resolution | [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression) | Η στόχευση ανάλυση σε σχέση με το μέγεθος με το οποίο εμφανίζεται κάθε εικόνα.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/el/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) δεν αλλάζει τις εικόνες. |

### Παρατηρήσεις

Οι εικόνες που ήδη έχουν τη στόχευση ανάλυση ή είναι χαμηλότερης ανάλυσης παραμένουν αμετάβλητες· οι εικόνες δεν αυξάνονται ποτέ σε ανάλυση.


Δεν υποβάλλονται σε επεξεργασία: φόντα διαφανειών, γεμίσματα κελιών πινάκων, διαγράμματα, SmartArt, εικόνες GIF (για διατήρηση της κίνησης),
            εικόνες SVG και μετααρχείου (EMF/WMF).

Οι περικομμένες περιοχές αφαιρούνται μόνιμα και δεν μπορούν να επαναφερθούν στο PowerPoint.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` είναι `None`. |



### Δείτε επίσης
* κλάση [`Compress`](/slides/python-net/el/aspose.slides.lowcode/compress)
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* απαρίθμηση [`PicturesCompression`](/slides/python-net/el/aspose.slides.export/picturescompression)
* μονάδα [`aspose.slides.lowcode`](/slides/python-net/el/aspose.slides.lowcode)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)