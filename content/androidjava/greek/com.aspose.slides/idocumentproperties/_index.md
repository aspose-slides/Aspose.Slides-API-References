---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents properties of a presentation.
type: docs
url: /el/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Αναπαριστά τις ιδιότητες μιας παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Επιστρέφει την έκδοση της εφαρμογής. |
| [getNameOfApplication()](#getNameOfApplication--) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [getCompany()](#getCompany--) | Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. |
| [getManager()](#getManager--) | Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. |
| [setManager(String value)](#setManager-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. |
| [getPresentationFormat()](#getPresentationFormat--) | Επιστρέφει ή ορίζει τη προτιμώμενη μορφή μιας παρουσίασης. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Επιστρέφει ή ορίζει τη προτιμώμενη μορφή μιας παρουσίασης. |
| [getSharedDoc()](#getSharedDoc--) | Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών ατόμων. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών ατόμων. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. |
| [getTitle()](#getTitle--) | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. |
| [getSubject()](#getSubject--) | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. |
| [getAuthor()](#getAuthor--) | Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. |
| [getKeywords()](#getKeywords--) | Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. |
| [getComments()](#getComments--) | Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. |
| [setComments(String value)](#setComments-java.lang.String-) | Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. |
| [getCategory()](#getCategory--) | Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. |
| [getCreatedTime()](#getCreatedTime--) | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. |
| [getLastSavedTime()](#getLastSavedTime--) | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. |
| [getLastPrinted()](#getLastPrinted--) | Επιστρέφει την ημερομηνία τελευταίας εκτύπωσης μιας παρουσίασης. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Επιστρέφει την ημερομηνία τελευταίας εκτύπωσης μιας παρουσίασης. |
| [getLastSavedBy()](#getLastSavedBy--) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. |
| [getRevisionNumber()](#getRevisionNumber--) | Επιστρέφει ή ορίζει το αριθμό αναθεώρησης της παρουσίασης. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Επιστρέφει ή ορίζει το αριθμό αναθεώρησης της παρουσίασης. |
| [getContentStatus()](#getContentStatus--) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [getContentType()](#getContentType--) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Υποδεικνύει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Υποδεικνύει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Υποδεικνύει εάν οι υπερσυνδέσμοι σε ένα έγγραφο είναι ενημερωμένοι. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Υποδεικνύει εάν οι υπερσυνδέσμοι σε ένα έγγραφο είναι ενημερωμένοι. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Προσδιορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Προσδιορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [getSlides()](#getSlides--) | Προσδιορίζει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getHiddenSlides()](#getHiddenSlides--) | Προσδιορίζει τον αριθμό κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getNotes()](#getNotes--) | Προσδιορίζει τον αριθμό διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. |
| [getParagraphs()](#getParagraphs--) | Προσδιορίζει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο, εάν ισχύει. |
| [getWords()](#getWords--) | Προσδιορίζει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. |
| [getMultimediaClips()](#getMultimediaClips--) | Προσδιορίζει τον συνολικό αριθμό ήχου ή βίντεο κλιπ που υπάρχουν στο έγγραφο. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Προσδιορίζει τον τίτλο κάθε τμήματος εγγράφου. |
| [getHeadingPairs()](#getHeadingPairs--) | Υποδεικνύει τη ομαδοποίηση των τμημάτων εγγράφου και τον αριθμό τμημάτων σε κάθε ομάδα. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Επιστρέφει τον αριθμό προσαρμοσμένων ιδιοτήτων που περιέχονται στην συλλογή. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Αφαιρεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με ένα συγκεκριμένο όνομα. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [clearCustomProperties()](#clearCustomProperties--) | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Sets a named boolean custom property. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Sets a named integer custom property. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Sets a named DateTime custom property. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Sets a named string custom property. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Sets a named float custom property. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Sets a named double custom property. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Επιστρέφει την έκδοση της εφαρμογής. Μόνο ανάγνωση String.

--------------------

Το περιεχόμενο αυτού του στοιχείου πρέπει να έχει τη μορφή XX.YYYY, όπου X και Y αντιπροσωπεύουν αριθμητικές τιμές· διαφορετικά, το έγγραφο θεωρείται μη συμμορφωμένο. Το Aspose.Slides αναπαριστά την έκδοσή του στη μορφή XX.YY.ZZ, όπου: XX - κύρια έκδοση YY - δευτερεύουσα έκδοση ZZ - έκδοση διορθώσεων. Για παράδειγμα, η τιμή 23.0105 σημαίνει την έκδοση 23.1.5 του Aspose.Slides.

**Επιστρέφει:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Επιστρέφει ή ορίζει τη προτιμώμενη μορφή μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Επιστρέφει ή ορίζει τη προτιμώμενη μορφή μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών ατόμων. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών ατόμων. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Επιστρέφει ή ορίζει τον συγγραφέα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/εγγραφή java.util.Date.

**Επιστρέφει:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/εγγραφή java.util.Date.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC.P Μόνο ανάγνωση στην περίπτωση Presentation.DocumentProperties (γιατί ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του αντικειμένου DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Επιστρέφει:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC.P Μόνο ανάγνωση στην περίπτωση Presentation.DocumentProperties (γιατί ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του αντικειμένου DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Επιστρέφει την ημερομηνία τελευταίας εκτύπωσης μιας παρουσίασης. Ανάγνωση/εγγραφή java.util.Date.

**Επιστρέφει:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Επιστρέφει την ημερομηνία τελευταίας εκτύπωσης μιας παρουσίασης. Ανάγνωση/εγγραφή java.util.Date.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Υποδεικνύει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας του εγγράφου στην οθόνη. Ορίστε το σε **false** για να ενεργοποιήσετε το περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Υποδεικνύει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιήσετε την κλιμάκωση της μικρογραφίας του εγγράφου στην οθόνη. Ορίστε το σε **false** για να ενεργοποιήσετε το περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Υποδεικνύει εάν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι έχουν ενημερωθεί. Ορίστε το σε **false** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ξεπερασμένοι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Υποδεικνύει εάν οι υπερσύνδεσμοι σε ένα έγγραφο είναι ενημερωμένοι. Ορίστε το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσύνδεσμοι έχουν ενημερωθεί. Ορίστε το σε **false** για να υποδείξετε ότι οι υπερσύνδεσμοι είναι ξεπερασμένοι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Προσδιορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Προσδιορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσμων με τους νέους υπερσυνδέσμους που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Προσδιορίζει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Προσδιορίζει τον αριθμό κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Προσδιορίζει τον αριθμό διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Προσδιορίζει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο, εάν ισχύει. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Προσδιορίζει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Προσδιορίζει τον συνολικό αριθμό ήχου ή βίντεο κλιπ που υπάρχουν στο έγγραφο. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Προσδιορίζει τον τίτλο κάθε τμήματος εγγράφου. Αυτά τα τμήματα δεν είναι πραγματικά τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις τμημάτων. Μόνο ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Υποδεικνύει τη ομαδοποίηση των τμημάτων εγγράφου και τον αριθμό τμημάτων σε κάθε ομάδα. Μόνο ανάγνωση IHeadingPair[].

**Επιστρέφει:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται στην συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης της προσαρμοσμένης ιδιότητας που θα ληφθεί. |

**Επιστρέφει:**
java.lang.String - Όνομα προσαρμοσμένης ιδιότητας στο καθορισμένο δείκτη.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Αφαιρεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με το καθορισμένο όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα αφαιρεθεί. |

**Επιστρέφει:**
boolean - Επιστρέφει true εάν αφαιρέθηκε η ιδιότητα, false διαφορετικά.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με το καθορισμένο όνομα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ελεγχθεί. |

**Επιστρέφει:**
boolean - Επιστρέφει true εάν η ιδιότητα υπάρχει, false διαφορετικά.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το καθορισμένο όνομα. Ανάγνωση/εγγραφή Object.

--------------------

Η τιμή μπορεί να είναι **int**, **float**, **double**, **String**, **boolean** ή **Date**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Επιστρέφει:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το καθορισμένο όνομα. Ανάγνωση/εγγραφή Object.

--------------------

Η τιμή μπορεί να είναι **int**, **float**, **double**, **String**, **boolean** ή **Date**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Λαμβάνει μια ονομαστική τιμή boolean από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | boolean[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Λαμβάνει μια ονομαστική τιμή ακεραίου από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | int[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Λαμβάνει μια ονομαστική τιμή DateTime από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | java.util.Date[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Λαμβάνει μια ονομαστική τιμή string από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | java.lang.String[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Λαμβάνει μια ονομαστική τιμή float από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | float[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Λαμβάνει μια ονομαστική τιμή double από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί. |
| value | double[] | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Ορίζει μια ονομαστική boolean προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | boolean | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Ορίζει μια ονομαστική ακέραια προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | int | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Ορίζει μια ονομαστική DateTime προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | java.util.Date | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Ορίζει μια ονομαστική string προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | java.lang.String | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Ορίζει μια ονομαστική float προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | float | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Ορίζει μια ονομαστική double προσαρμοσμένη ιδιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα οριστεί |
| value | double | Τιμή προσαρμοσμένης ιδιότητας |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Λαμβάνει έναν πίνακα ευαισθητοτήτων από τις προσαρμοσμένες ιδιότητες του εγγράφου (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Λάβετε ετικέτες ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Προσθέστε την ετικέτα στη συλλογή
>          // Εδώ μπορείτε να προσθέσετε έναν έλεγχο για την εγκυρότητα των πληροφοριών της ετικέτας (η ετικέτα είναι διαθέσιμη, κλπ)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
com.aspose.slides.ISensitivityLabel[]