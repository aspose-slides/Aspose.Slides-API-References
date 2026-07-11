---
title: ResponsiveHtmlController
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιδραστικός HTML Controller
type: docs
url: /el/com.aspose.slides/responsivehtmlcontroller/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IResponsiveHtmlController](../../com.aspose.slides/iresponsivehtmlcontroller)
```
public class ResponsiveHtmlController implements IResponsiveHtmlController
```

Responsive HTML Controller
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ResponsiveHtmlController()](#ResponsiveHtmlController--) | Δημιουργεί νέα παρουσία |
| [ResponsiveHtmlController(IHtmlFormattingController controller)](#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-) | Δημιουργεί νέα παρουσία |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### ResponsiveHtmlController() {#ResponsiveHtmlController--}
```
public ResponsiveHtmlController()
```

Δημιουργεί νέα παρουσία

### ResponsiveHtmlController(IHtmlFormattingController controller) {#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public ResponsiveHtmlController(IHtmlFormattingController controller)
```

Δημιουργεί νέα παρουσία

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Ελεγκτής μορφοποίησης HTML |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράφει κάτι στον γεννήτρια, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα προστεθεί και η νέα εικόνα θα ξεκινήσει επάνω στην προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράφει κάτι στον γεννήτρια, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα προστεθεί και η νέα εικόνα θα ξεκινήσει επάνω στην προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |