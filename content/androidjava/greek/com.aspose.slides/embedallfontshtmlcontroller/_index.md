---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Η κλάση ελέγχου μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση όλων των γραμματοσειρών της παρουσίασης σε μορφή WOFF.
type: docs
url: /el/com.aspose.slides/embedallfontshtmlcontroller/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Η κλάση ελεγκτή μορφοποίησης που χρησιμοποιείται για την ενσωμάτωση όλων των γραμματοσειρών της παρουσίασης σε μορφή WOFF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Δημιουργεί νέα παρουσία |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Δημιουργεί νέα παρουσία |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document header. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document footer. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide header. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide footer. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Write all fonts contained in [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Γράφει δεδομένα ως base64 στο ίδιο το έγγραφο HTML |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Δημιουργεί νέα παρουσία

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Δημιουργεί νέα παρουσία

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

Καλείται για τη γραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αυτή τη στιγμή αποδίδεται. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Καλείται για τη γραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| slide | [ISlide](../../com.aspose.slides/islide) | Διαφάνεια που αυτή τη στιγμή αποδίδεται. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στον δημιουργό, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, θα προστεθεί το τμήμα html και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που πρόκειται να αποδοθεί. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στον δημιουργό, η δημιουργία εικόνας της τρέχουσας διαφάνειας θα ολοκληρωθεί, θα προστεθεί το τμήμα html και θα ξεκινήσει νέα εικόνα πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Αντικείμενο εξόδου. |
| shape | [IShape](../../com.aspose.slides/ishape) | Σχήμα που αποδιδόταν τελευταίο. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Γράφει όλες τις γραμματοσειρές που περιέχονται στο [Presentation](../../com.aspose.slides/presentation).

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
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Αντικατασταθείσα γραμματοσειρά (αν πραγματοποιήθηκε αντικατάσταση γραμματοσειράς), αλλιώς null |
| fontStyle | java.lang.String | Στυλ γραμματοσειράς |
| fontWeight | java.lang.String | Βάρος γραμματοσειράς |
| fontData | byte[] | Δεδομένα γραμματοσειράς |