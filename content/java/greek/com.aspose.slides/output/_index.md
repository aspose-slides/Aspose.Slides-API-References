---
title: Output
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή στοιχείων εξόδου για το IWebDocument.
type: docs
url: /el/com.aspose.slides/output/
---
**Κληρονομικότητα:**
java.lang.Object
```
public final class Output
```

Αντιπροσωπεύει μια συλλογή στοιχείων εξόδου για το IWebDocument.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Adds an output element for the audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Προσθέτει ένα στοιχείο εξόδου για το αντικείμενο περιβάλλοντος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| templateKey | java.lang.String | Το κλειδί του προτύπου που χρησιμοποιείται για τη μετατροπή του αντικειμένου περιβάλλοντος πριν από την έξοδο. |
| contextObject | TContextObject | Αντικείμενο περιβάλλοντος. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το αντικείμενο περιβάλλοντος.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Προσθέτει ένα στοιχείο εξόδου για την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Εικόνα προς εξαγωγή. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για την εικόνα.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Προσθέτει ένα στοιχείο εξόδου για την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα προς εξαγωγή. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για την εικόνα.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Προσθέτει ένα στοιχείο εξόδου για το βίντεο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Βίντεο προς εξαγωγή. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το βίντεο.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Προσθέτει ένα στοιχείο εξόδου για το ήχο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ήχος προς εξαγωγή. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το ήχο.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Δημιουργεί και προσθέτει ένα στοιχείο αρχείου εξόδου για τη συγκεκριμένη γραμματοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτεί η έξοδος της γραμματοσειράς. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Τα δεδομένα γραμματοσειράς που θα γραφούν στην έξοδο. |
| fontStyle | int | Το στυλ της γραμματοσειράς (π.χ. Κανονικό, Έντονο, Πλάγιο). |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Ένα [IOutputFile](../../com.aspose.slides/ioutputfile) παράδειγμα για τη δημιουργημένη γραμματοσειρά.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Προσθέτει ένα στοιχείο εξόδου για το περιεχόμενο κειμένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| textContent | java.lang.String | Περιεχόμενο για εξαγωγή. |

**Επιστρέφει:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το περιεχόμενο κειμένου.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Δεσμεύει πόρο στο αρχείο εξόδου.

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