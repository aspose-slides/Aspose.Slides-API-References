---
title: VideoPlayerHtmlController
second_title: Αναφορά API Aspose.Slides για Java
description: Αυτή η κλάση επιτρέπει την εξαγωγή βίντεο και αρχείων ήχου σε HTML
type: docs
url: /el/com.aspose.slides/videoplayerhtmlcontroller/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Αυτή η κλάση επιτρέπει την εξαγωγή βίντεο και αρχείων ήχου σε HTML
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Δημιουργεί μια νέα παρουσία του ελεγκτή |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


Δημιουργεί μια νέα παρουσία του ελεγκτή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Η διαδρομή όπου θα παραχθούν τα αρχεία βίντεο και ήχου |
| fileName | java.lang.String | Το όνομα του αρχείου HTML |
| baseUri | java.lang.String | Το βασικό URI που θα χρησιμοποιηθεί για τη δημιουργία συνδέσμων |

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


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στο generator, η τρέχουσα δημιουργία εικόνας διαφάνειας θα ολοκληρωθεί, θα προστεθεί το html απόσπασμα και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Καλείται πριν από την απόδοση του σχήματος. Καλείται μία φορά για κάθε σχήμα. Εάν αυτή η λειτουργία γράψει κάτι στο generator, η τρέχουσα δημιουργία εικόνας διαφάνειας θα ολοκληρωθεί, θα προστεθεί το html απόσπασμα και μια νέα εικόνα θα ξεκινήσει πάνω από την προηγούμενη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


Αυτή η λειτουργία καλείται πριν από την απόδοση του σχήματος σε SVG ώστε να επιτρέψει στον χρήστη να ελέγξει το τελικό SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου. Δεν εγγυάται ότι δεν θα υπάρξουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά με διαφορετικό id.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Επιστρέφει:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


Επιστρέφει ένα URL σε ένα εξωτερικό αντικείμενο. Αυτή η μέθοδος καλείται πάντα εάν \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) επέστρεψε [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) και μπορεί να κληθεί εάν \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) επέστρεψε [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) αλλά η ενσωμάτωση είναι αδύνατη. Μπορεί να κληθεί πολλαπλές φορές για το ίδιο αναγνωριστικό αντικειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Επιστρέφει:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


Αποθηκεύει το εξωτερικό αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |