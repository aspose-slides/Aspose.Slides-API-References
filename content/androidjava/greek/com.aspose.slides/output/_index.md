---
title: Output
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
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
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Προσθέτει ένα στοιχείο εξόδου για το αντικείμενο περιεχομένου. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Προσθέτει ένα στοιχείο εξόδου για την εικόνα. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Προσθέτει ένα στοιχείο εξόδου για την εικόνα. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Προσθέτει ένα στοιχείο εξόδου για το βίντεο. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Προσθέτει ένα στοιχείο εξόδου για τον ήχο. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Δημιουργεί και προσθέτει ένα στοιχείο αρχείου εξόδου για τη συγκεκριμένη γραμματοσειρά. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Προσθέτει ένα στοιχείο εξόδου για το κείμενο. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Συνδέει πόρο με αρχείο εξόδου. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Επιστρέφει τη διαδρομή για έναν δεδομένο πόρο. |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Προσθέτει ένα στοιχείο εξόδου για το αντικείμενο περιεχομένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| templateKey | java.lang.String | Το κλειδί του προτύπου που χρησιμοποιείται για τη μετασχηματισμό του αντικειμένου περιεχομένου πριν την έξοδο. |
| contextObject | TContextObject | Αντικείμενο περιεχομένου. |

**Επιστρέφει:**  
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το αντικείμενο περιεχομένου.

### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Προσθέτει ένα στοιχείο εξόδου για την εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Εικόνα προς έξοδο. |

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
| image | [IImage](../../com.aspose.slides/iimage) | Εικόνα προς έξοδο. |

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
| video | [IVideo](../../com.aspose.slides/ivideo) | Βίντεο προς έξοδο. |

**Επιστρέφει:**  
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το βίντεο.

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Προσθέτει ένα στοιχείο εξόδου για τον ήχο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ήχος προς έξοδο. |

**Επιστρέφει:**  
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για τον ήχο.

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Δημιουργεί και προσθέτει ένα στοιχείο αρχείου εξόδου για τη συγκεκριμένη γραμματοσειρά.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Η διαδρομή αρχείου όπου θα αποθηκευτεί η έξοδος της γραμματοσειράς. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Τα δεδομένα γραμματοσειράς που θα γραφτούν στην έξοδο. |
| fontStyle | int | Το στυλ της γραμματοσειράς (π.χ., Κανονικό, Έντονο, Πλάγιο). |

**Επιστρέφει:**  
[IOutputFile](../../com.aspose.slides/ioutputfile) - Μία [IOutputFile](../../com.aspose.slides/ioutputfile) παρουσία για τη δημιουργηθείσα γραμματοσειρά.

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Προσθέτει ένα στοιχείο εξόδου για το κείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | java.lang.String | Διαδρομή εξόδου. |
| textContent | java.lang.String | Περιεχόμενο προς έξοδο. |

**Επιστρέφει:**  
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) αντικείμενο για το κείμενο.

### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Συνδέει πόρο με αρχείο εξόδου.

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