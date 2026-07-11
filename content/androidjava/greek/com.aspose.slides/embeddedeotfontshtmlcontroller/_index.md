---
title: EmbeddedEotFontsHtmlController
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Η κλάση ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση γραμματοσειρών σε μορφή EOT
type: docs
url: /el/com.aspose.slides/embeddedeotfontshtmlcontroller/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IEmbeddedEotFontsHtmlController](../../com.aspose.slides/iembeddedeotfontshtmlcontroller)
```
public class EmbeddedEotFontsHtmlController implements IEmbeddedEotFontsHtmlController
```

Η κλάση ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση γραμματοσειρών σε μορφή EOT
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
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Ελεγκτής μορφοποίησης HTML. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για να γράψει την κεφαλίδα του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για να γράψει το υποσέλιδο του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Καλείται για να γράψει την κεφαλίδα της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Καλείται για να γράψει το υποσέλιδο της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Αν αυτή η λειτουργία γράψει κάτι στον γεννήτρια, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το πρόσθετο τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα στην κορυφή της προηγούμενης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Αν αυτή η λειτουργία γράψει κάτι στον γεννήτρια, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το πρόσθετο τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα στην κορυφή της προηγούμενης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |