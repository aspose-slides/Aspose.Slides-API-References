---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides για την αναφορά API της Java
description: Η κλάση ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση όλων των γραμματοσειρών παρουσίασης σε μορφή WOFF.
type: docs
url: /el/com.aspose.slides/embedallfontshtmlcontroller/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Η κατηγορία ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση όλων των γραμματοσειρών παρουσίασης σε μορφή WOFF.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Δημιουργεί νέο αντικείμενο |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Δημιουργεί νέο αντικείμενο |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν από τη σχεδίαση του σχήματος. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Καλείται πριν από τη σχεδίαση του σχήματος. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Γράψτε όλες τις γραμματοσειρές που περιέχονται στο [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Γράφει δεδομένα ως base64 στο ίδιο το έγγραφο HTML |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


Δημιουργεί νέο αντικείμενο

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


Δημιουργεί νέο αντικείμενο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Γραμματοσειρές που θα εξαιρεθούν από την ενσωμάτωση |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για τη γραφή της κεφαλίδας του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που αυτή τη στιγμή αποδίδεται. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Καλείται για τη γραφή του υποσέλιδου του εγγράφου html. Καλείται μία φορά ανά μετατροπή παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που αυτή τη στιγμή αποδίδεται. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για καθέ διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αυτή τη στιγμή αποδίδεται. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για καθέ διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αυτή τη στιγμή αποδίδεται. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από τη σχεδίαση του σχήματος. Καλείται μία φορά για καθέ σχήμα. Αν αυτή η συνάρτηση γράψει κάτι στον generator, η δημιουργία εικόνας τρέχουσας διαφάνειας θα τερματιστεί, το προστεθέν τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που πρόκειται να αποδοθεί. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από τη σχεδίαση του σχήματος. Καλείται μία φορά για καθέ σχήμα. Αν αυτή η συνάρτηση γράψει κάτι στον generator, η δημιουργία εικόνας τρέχουσας διαφάνειας θα τερματιστεί, το προστεθέν τμήμα html θα ενσωματωθεί και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Τελευταίο σχήμα που αποδόθηκε. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


Γράψτε όλες τις γραμματοσειρές που περιέχονται στο [Presentation](../../com.aspose.slides/presentation).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Παρουσίαση που αυτή τη στιγμή αποδίδεται. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


Γράφει δεδομένα ως base64 στο ίδιο το έγγραφο HTML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Γεννήτρια HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Γραμματοσειρά προς σειριοποίηση |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Αντικατεστημένη γραμματοσειρά (αν έγινε αντικατάσταση γραμματοσειράς), αλλιώς null |
| fontStyle | java.lang.String | Στυλ γραμματοσειράς |
| fontWeight | java.lang.String | Βάρος γραμματοσειράς |
| fontData | byte[] | Δεδομένα γραμματοσειράς |