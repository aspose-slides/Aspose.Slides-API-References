---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Ελέγχει τη δημιουργία αρχείου html.
type: docs
url: /el/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Ελέγχει τη δημιουργία αρχείου html.
## Methods

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για την εγγραφή της κεφαλίδας του εγγράφου html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για την εγγραφή του υποσέλιδου του εγγράφου html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για την εγγραφή της κεφαλίδας της διαφάνειας html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για την εγγραφή του υποσέλιδου της διαφάνειας html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν από την απόδοση του σχήματος. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν από την απόδοση του σχήματος. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για την εγγραφή της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που επεξεργάζεται αυτή τη στιγμή. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για την εγγραφή του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που επεξεργάζεται αυτή τη στιγμή. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Καλείται για την εγγραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που επεξεργάζεται αυτή τη στιγμή. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Καλείται για την εγγραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που επεξεργάζεται αυτή τη στιγμή. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον γεννήτρια, η τρέχουσα δημιουργία εικόνας της διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα προσαρτηθεί και μια νέα εικόνα θα ξεκινήσει πάνω στην προηγούμενη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που πρόκειται να αποδοθεί. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η συνάρτηση γράψει κάτι στον γεννήτρια, η τρέχουσα δημιουργία εικόνας της διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα προσαρτηθεί και μια νέα εικόνα θα ξεκινήσει πάνω στην προηγούμενη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που αποδόθηκε τελευταίο. |