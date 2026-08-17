---
title: EmbeddedEotFontsHtmlController
second_title: Aspose.Slides για την Αναφορά API της Java
description: Η κλάση ελεγκτή μορφοποίησης για χρήση κατά την ενσωμάτωση γραμματοσειρών σε μορφή EOT
type: docs
url: /el/com.aspose.slides/embeddedeotfontshtmlcontroller/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEmbeddedEotFontsHtmlController](../../com.aspose.slides/iembeddedeotfontshtmlcontroller)
```
public class EmbeddedEotFontsHtmlController implements IEmbeddedEotFontsHtmlController
```

Η κλάση ελεγκτή μορφοποίησης για χρήση κατά την ενσωμάτωση γραμματοσειρών σε μορφή EOT
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EmbeddedEotFontsHtmlController()](#EmbeddedEotFontsHtmlController--) | Δημιουργεί νέο αντικείμενο. |
| [EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Δημιουργεί νέο αντικείμενο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedEotFontsHtmlController() {#EmbeddedEotFontsHtmlController--}
```
public EmbeddedEotFontsHtmlController()
```


Δημιουργεί νέο αντικείμενο.

### EmbeddedEotFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)
```


Δημιουργεί νέο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Έλεγχος μορφοποίησης HTML. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για τη σύνταξη της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για τη σύνταξη του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Καλείται για τη σύνταξη της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Καλείται για τη σύνταξη του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η τρέχουσα δημιουργία εικόνας της διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα εισαχθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η τρέχουσα δημιουργία εικόνας της διαφάνειας θα ολοκληρωθεί, το προστεθέν τμήμα html θα εισαχθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |