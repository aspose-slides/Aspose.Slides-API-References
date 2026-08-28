---
title: Convert
second_title: Aspose.Sildes για PHP μέσω αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/convert/
---
## Convert κλάση

Αναπαριστά ένα σύνολο μεθόδων που προορίζονται για τη μετατροπή του Presentation.
 
### Convert {#Convert}

| Όνομα | Περιγραφή |
| --- | --- |
| Convert() |  |

**Επιστρέφει:**  
Convert


---


### autoByExtension {#autoByExtension}

| Όνομα | Περιγραφή |
| --- | --- |
| autoByExtension (String, String) | Μετατρέπει το Presentation χρησιμοποιώντας την παρεχόμενη επέκταση διαδρομής εξόδου για να προσδιορίσει την απαιτούμενη μορφή εξαγωγής. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | String | Διαδρομή της εισαγόμενης παρουσίασης |
| outPath | String | Διαδρομή εξόδου |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Εάν η μορφή είναι άγνωστη ή δεν υποστηρίζεται |


---


### toJpeg {#toJpeg}

| Όνομα | Περιγραφή |
| --- | --- |
| toJpeg ([Presentation](../presentation), String) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toJpeg {#toJpeg}

| Όνομα | Περιγραφή |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, Dimension) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |
| imageSize | Dimension | Το μέγεθος κάθε παραγόμενης εικόνας. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toJpeg {#toJpeg}

| Όνομα | Περιγραφή |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |
| scale | float | Ο συντελεστής κλίμακας που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [RenderingOptions](../renderingoptions) | Οι επιλογές απόδοσης. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toPdf {#toPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| toPdf (String, String) | Μετατρέπει το Presentation σε PDF. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | String | Διαδρομή της εισαγόμενης παρουσίασης |
| outPath | String | Διαδρομή εξόδου |

**Επιστρέφει:**  
void


---


### toPdf {#toPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| toPdf (String, String, [PdfOptions](../pdfoptions)) | Μετατρέπει το Presentation σε PDF. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | String | Διαδρομή της εισαγόμενης παρουσίασης |
| outPath | String | Διαδρομή εξόδου |
| options | [PdfOptions](../pdfoptions) | Επιλογές εξόδου PDF |

**Επιστρέφει:**  
void


---


### toPdf {#toPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| toPdf ([Presentation](../presentation), String) | Μετατρέπει το Presentation σε PDF. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Εισαγόμενη παρουσίαση |
| outPath | String | Διαδρομή εξόδου |

**Επιστρέφει:**  
void


---


### toPdf {#toPdf}

| Όνομα | Περιγραφή |
| --- | --- |
| toPdf ([Presentation](../presentation), String, [PdfOptions](../pdfoptions)) | Μετατρέπει το Presentation σε PDF. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Εισαγόμενη παρουσίαση |
| outPath | String | Διαδρομή εξόδου |
| options | [PdfOptions](../pdfoptions) | Επιλογές εξόδου PDF |

**Επιστρέφει:**  
void


---


### toPng {#toPng}

| Όνομα | Περιγραφή |
| --- | --- |
| toPng ([Presentation](../presentation), String) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.png", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toPng {#toPng}

| Όνομα | Περιγραφή |
| --- | --- |
| toPng ([Presentation](../presentation), String, Dimension) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.png", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |
| imageSize | Dimension | Το μέγεθος κάθε παραγόμενης εικόνας. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toPng {#toPng}

| Όνομα | Περιγραφή |
| --- | --- |
| toPng ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.png", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |
| scale | float | Ο συντελεστής κλίμακας που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [RenderingOptions](../renderingoptions) | Οι επιλογές απόδοσης. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toSvg {#toSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| toSvg (String) | Μετατρέπει το Presentation σε SVG. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | String | Διαδρομή της εισαγόμενης παρουσίασης |

**Επιστρέφει:**  
void


---


### toSvg {#toSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| toSvg (String, [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Μετατρέπει το Presentation σε SVG. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | String | Διαδρομή της εισαγόμενης παρουσίασης |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Αντίστροφη κλήση που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |

**Επιστρέφει:**  
void


---


### toSvg {#toSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Μετατρέπει το Presentation σε SVG. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Εισαγόμενη παρουσίαση |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Αντίστροφη κλήση που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |

**Επιστρέφει:**  
void


---


### toSvg {#toSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| toSvg ([Presentation](../presentation), [SVGOptions](../svgoptions)) | Μετατρέπει το Presentation σε SVG. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Εισαγόμενη παρουσίαση |
| options | [SVGOptions](../svgoptions) | Επιλογές εξαγωγής SVG |

**Επιστρέφει:**  
void


---


### toSvg {#toSvg}

| Όνομα | Περιγραφή |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback), [SVGOptions](../svgoptions)) | Μετατρέπει το Presentation σε SVG. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Εισαγόμενη παρουσίαση |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Αντίστροφη κλήση που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |
| options | [SVGOptions](../svgoptions) | Επιλογές εξαγωγής SVG |

**Επιστρέφει:**  
void


---


### toTiff {#toTiff}

| Όνομα | Περιγραφή |
| --- | --- |
| toTiff ([Presentation](../presentation), String) | Μετατρέπει την εισαγόμενη παρουσίαση σε ένα σύνολο εικόνων μορφής TIFF. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |


---


### toTiff {#toTiff}

| Όνομα | Περιγραφή |
| --- | --- |
| toTiff ([Presentation](../presentation), String, [TiffOptions](../tiffoptions), boolean) | Μετατρέπει την εισαγόμενη παρουσίαση σε μορφή TIFF με προσαρμοσμένες επιλογές. Εάν το όνομα αρχείου εξόδου δοθεί ως "myPath/myFilename.tiff" και το multipage είναι false, το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename_N.tiff", όπου N είναι ο αριθμός της διαφάνειας. Διαφορετικά, εάν το multipage είναι true, το αποτέλεσμα θα είναι ένα πολυσελιδικό έγγραφο "myPath/myFilename.tiff". |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Η εισαγόμενη παρουσίαση. |
| outputFileName | String | Το όνομα του αρχείου εξόδου. |
| options | [TiffOptions](../tiffoptions) | Οι επιλογές αποθήκευσης TIFF. |
| multipage | boolean | Καθορίζει εάν το παραγόμενο έγγραφο TIFF πρέπει να είναι πολυσέλιδο. |

**Επιστρέφει:**  
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| null | ArgumentException |
