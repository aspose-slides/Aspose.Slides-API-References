---
title: Output
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή στοιχείων εξόδου για το IWebDocument.
type: docs
url: /el/com.aspose.slides/output/
---
**Κληρονομικότητα:**
java.lang.Object
```
public final class Output
```

Αναπαριστά μια συλλογή στοιχείων εξόδου για IWebDocument.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Προσθέτει ένα στοιχείο εξόδου για το αντικείμενο περιβάλλοντος. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Προσθέτει ένα στοιχείο εξόδου για την εικόνα. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Προσθέτει ένα στοιχείο εξόδου για την εικόνα. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Προσθέτει ένα στοιχείο εξόδου για το βίντεο. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Δημιουργεί και προσθέτει ένα στοιχείο αρχείου εξόδου για τη συγκεκριμένη γραμματοσειρά. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Προσθέτει ένα στοιχείο εξόδου για το περιεχόμενο κειμένου. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Συνδέει πόρο με το αρχείο εξόδου. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Επιστρέφει τη διαδρομή για έναν δεδομένο πόρο. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Προσθέτει ένα στοιχείο εξόδου για το αντικείμενο περιβάλλοντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| templateKey | java.lang.String | Το κλειδί του προτύπου που χρησιμοποιείται για τη μετατροπή του αντικειμένου περιβάλλοντος πριν την έξοδο. |
| contextObject | TContextObject | Αντικείμενο περιβάλλοντος. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the context object.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Προσθέτει ένα στοιχείο εξόδου για την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Εικόνα για έξοδο. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Προσθέτει ένα στοιχείο εξόδου για την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα για έξοδο. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Προσθέτει ένα στοιχείο εξόδου για το βίντεο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Βίντεο για έξοδο. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Δημιουργεί και προσθέτει ένα στοιχείο αρχείου εξόδου για τη συγκεκριμένη γραμματοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευθεί η έξοδος της γραμματοσειράς. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Τα δεδομένα γραμματοσειράς που θα γραφούν στην έξοδο. |
| fontStyle | int | Το στυλ της γραμματοσειράς (π.χ., Κανονικό, Έντονο, Πλάγιο). |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Ένα [IOutputFile](../../com.aspose.slides/ioutputfile) instance for the generated font.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Προσθέτει ένα στοιχείο εξόδου για το περιεχόμενο κειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| textContent | java.lang.String | Περιεχόμενο για έξοδο. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the text content.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Συνδέει πόρο με το αρχείο εξόδου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Αρχείο εξόδου. |
| obj | java.lang.Object | Αντικείμενο πόρου. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Επιστρέφει τη διαδρομή για έναν δεδομένο πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Αντικείμενο πόρου. |

**Επιστρέφει:**
java.lang.String - Διαδρομή πόρου.