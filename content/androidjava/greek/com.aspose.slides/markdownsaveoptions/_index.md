---
title: MarkdownSaveOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.
type: docs
url: /el/com.aspose.slides/markdownsaveoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Αναπαριστά επιλογές που ελέγχουν πώς η παρουσίαση πρέπει να αποθηκευτεί σε markdown.

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
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Κατασκευή. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getExportType()](#getExportType--) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [setExportType(int value)](#setExportType-int-) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [getBasePath()](#getBasePath--) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευθεί το έγγραφο με τους πόρους. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Καθορίζει τη βασική διαδρομή όπου θα αποθηκευθεί το έγγραφο με τους πόρους. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Καθορίζει το όνομα του φακέλου για την αποθήκευση των εικόνων. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Καθορίζει το όνομα του φακέλου για την αποθήκευση των εικόνων. |
| [getNewLineType()](#getNewLineType--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh) ή \\n(Unix) ή \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh) ή \\n(Unix) ή \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. |
| [getFlavor()](#getFlavor--) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [setFlavor(int value)](#setFlavor-int-) | Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Καθορίζει πώς θα πρέπει να αντιμετωπίζονται οι επαναλαμβανόμενοι απλοί χαρακτήρες κενό κατά την εξαγωγή σε Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Καθορίζει πώς θα πρέπει να αντιμετωπίζονται οι επαναλαμβανόμενοι απλοί χαρακτήρες κενό κατά την εξαγωγή σε Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Εάν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Εάν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Σχετίζεται με κάθε εικόνα που δεν είναι SVG (bitmap ή metafile) κατά την εξαγωγή σε Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Σχετίζεται με κάθε εικόνα SVG κατά την εξαγωγή σε Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Κατασκευή.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλεγμένη τιμή είναι  TextOnly .

**Επιστρέφει:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλεγμένη τιμή είναι  TextOnly .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Καθορίζει τη βασική διαδρομή όπου θα αποθηκευθεί το έγγραφο με τους πόρους. Η προεπιλεγμένη τιμή είναι ο τρέχων φάκελος της εφαρμογής.

**Επιστρέφει:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Καθορίζει τη βασική διαδρομή όπου θα αποθηκευθεί το έγγραφο με τους πόρους. Η προεπιλεγμένη τιμή είναι ο τρέχων φάκελος της εφαρμογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Καθορίζει το όνομα του φακέλου για την αποθήκευση των εικόνων. Η προεπιλεγμένη τιμή είναι  Images .

**Επιστρέφει:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Καθορίζει το όνομα του φακέλου για την αποθήκευση των εικόνων. Η προεπιλεγμένη τιμή είναι  Images .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh) ή \\n(Unix) ή \\r\\n(Windows). Η προεπιλεγμένη τιμή είναι  Unix .

**Επιστρέφει:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να έχει νέες γραμμές \\r(Macintosh) ή \\n(Unix) ή \\r\\n(Windows). Η προεπιλεγμένη τιμή είναι  Unix .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει σχόλια ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο πρέπει να εμφανίζει τον αριθμό κάθε διαφάνειας ή όχι. Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλεγμένη τιμή είναι  Multi-markdown .

**Επιστρέφει:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Καθορίζει την προδιαγραφή markdown για τη μετατροπή της παρουσίασης. Η προεπιλεγμένη τιμή είναι  Multi-markdown .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης "\{0\}", το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "\# Slide \{0\}" θα παράγει "\# Slide 1", "\# Slide 2", κ.λπ.

**Επιστρέφει:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Λαμβάνει ή ορίζει τη συμβολοσειρά μορφής που χρησιμοποιείται για τις κεφαλίδες αριθμού διαφάνειας στην έξοδο Markdown. Η μορφή πρέπει να περιλαμβάνει το σύμβολο κράτησης θέσης "\{0\}", το οποίο θα αντικατασταθεί με τον δείκτη της διαφάνειας κατά την εξαγωγή. Παράδειγμα: "\# Slide \{0\}" θα παράγει "\# Slide 1", "\# Slide 2", κ.λπ.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Καθορίζει πώς θα πρέπει να αντιμετωπίζονται οι επαναλαμβανόμενοι απλοί χαρακτήρες κενό κατά την εξαγωγή σε Markdown. Αυτή η ιδιότητα ορίζει αν τα διαδοχικά κενά είναι: - διατηρημένα ως απλοί χαρακτήρες κενό, - εναλλασσόμενα μεταξύ απλών κενών και μη-διασπαστικών χαρακτήρων (�), - ή εντελώς αντικατεστημένα (μετά το πρώτο) με μη-διασπαστικό κενό για τη διατήρηση της οπτικής στοίχισης στην έξοδο Markdown. Η προεπιλεγμένη τιμή είναι [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Επιστρέφει:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Καθορίζει πώς θα πρέπει να αντιμετωπίζονται οι επαναλαμβανόμενοι απλοί χαρακτήρες κενό κατά την εξαγωγή σε Markdown. Αυτή η ιδιότητα ορίζει αν τα διαδοχικά κενά είναι: - διατηρημένα ως απλοί χαρακτήρες κενό, - εναλλασσόμενα μεταξύ απλών κενών και μη-διασπαστικών χαρακτήρων (�), - ή εντελώς αντικατεστημένα (μετά το πρώτο) με μη-διασπαστικό κενό για τη διατήρηση της οπτικής στοίχισης στην έξοδο Markdown. Η προεπιλεγμένη τιμή είναι [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Εάν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Εάν οριστεί σε true, αφαιρεί κενές ή μόνο με κενά γραμμές από την τελική έξοδο Markdown. Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Σχετίζεται με κάθε εικόνα που δεν είναι SVG (bitmap ή metafile) κατά την εξαγωγή σε Markdown. Επιτρέπει την προσαρμογή του τρόπου αποθήκευσης και αναφοράς της εικόνας. Εάν δεν επεξεργαστεί, η εικόνα αποθηκεύεται τοπικά με σχετικό σύνδεσμο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown image saving event. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Σχετίζεται με κάθε εικόνα SVG κατά την εξαγωγή σε Markdown. Επιτρέπει την παράκαμψη της προεπιλεγμένης αποθήκευσης και δημιουργίας συνδέσμου. Εάν δεν επεξεργαστεί, το SVG αποθηκεύεται τοπικά με σχετικό σύνδεσμο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG image saving event. |