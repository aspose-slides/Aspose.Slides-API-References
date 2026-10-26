---
title: IHtmlFormattingController
second_title: Aspose.Slides για την Αναφορά API Java
description: Ελέγχει τη δημιουργία αρχείου html.
type: docs
url: /el/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Ελέγχει τη δημιουργία αρχείου html.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν την απόδοση του σχήματος. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν την απόδοση του σχήματος. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που αποδίδεται αυτήν τη στιγμή. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που αποδίδεται αυτήν τη στιγμή. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αποδίδεται αυτήν τη στιγμή. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αποδίδεται αυτήν τη στιγμή. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει οτιδήποτε στον δημιουργό, η τρέχουσα δημιουργία εικόνας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα εισαχθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που πρόκειται να αποδοθεί. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει οτιδήποτε στον δημιουργό, η τρέχουσα δημιουργία εικόνας διαφάνειας θα ολοκληρωθεί, το προστιθέμενο απόσπασμα html θα εισαχθεί και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που αποδίδεται τελευταίο. |