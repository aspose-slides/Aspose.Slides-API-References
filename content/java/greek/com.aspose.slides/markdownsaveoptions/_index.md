---
title: MarkdownSaveOptions
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.
type: docs
url: /el/com.aspose.slides/markdownsaveoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Αναπαριστά τις επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExportType()](#getExportType--) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [setExportType(int value)](#setExportType-int-) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [getBasePath()](#getBasePath--) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Καθορίζει το όνομα φακέλου για την αποθήκευση εικόνων. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Καθορίζει το όνομα φακέλου για την αποθήκευση εικόνων. |
| [getNewLineType()](#getNewLineType--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. |
| [getFlavor()](#getFlavor--) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [setFlavor(int value)](#setFlavor-int-) | Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Καθορίζει πώς πρέπει να διαχειρίζονται οι επαναλαμβανόμενοι κανονικοί χαρακτήρες διαστήματος κατά την εξαγωγή Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Καθορίζει πώς πρέπει να διαχειρίζονται οι επαναλαμβανόμενοι κανονικοί χαρακτήρες διαστήματος κατά την εξαγωγή Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Αν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Αν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Συμβαίνει για κάθε εικόνα μη-SVG (bitmap ή metafile) κατά την εξαγωγή Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Συμβαίνει για κάθε εικόνα SVG κατά την εξαγωγή Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


Κατασκευαστής.

### getExportType() {#getExportType--}
```
public final int getExportType()
```


Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι  TextOnly .

**Επιστρέφει:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι  TextOnly .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής.

**Επιστρέφει:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


Καθορίζει τη βασική διαδρομή όπου θα αποθηκευτεί το έγγραφο με τους πόρους. Η προεπιλογή είναι ο τρέχων φάκελος της εφαρμογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


Καθορίζει το όνομα φακέλου για την αποθήκευση εικόνων. Η προεπιλογή είναι  Images .

**Επιστρέφει:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


Καθορίζει το όνομα φακέλου για την αποθήκευση εικόνων. Η προεπιλογή είναι  Images .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). Η προεπιλογή είναι  Unix .

**Επιστρέφει:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh), \\n(Unix) ή \\r\\n(Windows). Η προεπιλογή είναι  Unix .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι  Multi-markdown .

**Επιστρέφει:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


Καθορίζει τη προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλογή είναι  Multi-markdown .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το "\{0\}" placeholder, το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "\# Slide \{0\}" θα παράγει "\# Slide 1", "\# Slide 2", κ.λπ.

**Επιστρέφει:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το "\{0\}" placeholder, το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "\# Slide \{0\}" θα παράγει "\# Slide 1", "\# Slide 2", κ.λπ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


Καθορίζει πώς πρέπει να διαχειρίζονται οι επαναλαμβανόμενοι κανονικοί χαρακτήρες διαστήματος κατά την εξαγωγή Markdown. Η προεπιλογή είναι [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Επιστρέφει:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


Καθορίζει πώς πρέπει να διαχειρίζονται οι επαναλαμβανόμενοι κανονικοί χαρακτήρες διαστήματος κατά την εξαγωγή Markdown. Η προεπιλογή είναι [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


Αν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


Αν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


Συμβαίνει για κάθε εικόνα μη-SVG (bitmap ή metafile) κατά την εξαγωγή Markdown. Επιτρέπει προσαρμοσμένη αποθήκευση και αναφορά της εικόνας. Εάν δεν αντιμετωπιστεί, η εικόνα αποθηκεύεται τοπικά με σχετικό σύνδεσμο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Γεγονός αποθήκευσης εικόνας Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


Συμβαίνει για κάθε εικόνα SVG κατά την εξαγωγή Markdown. Επιτρέπει την παράκαμψη της προεπιλεγμένης αποθήκευσης και δημιουργίας συνδέσμου. Εάν δεν αντιμετωπιστεί, το SVG αποθηκεύεται τοπικά με σχετικό σύνδεσμο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Γεγονός αποθήκευσης SVG εικόνας Markdown. |