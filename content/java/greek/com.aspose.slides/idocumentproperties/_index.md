---
title: IDocumentProperties
second_title: Aspose.Slides for Java Αναφορά API
description: Αντιπροσωπεύει τις ιδιότητες μιας παρουσίασης.
type: docs
url: /el/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Αντιπροσωπεύει τις ιδιότητες μιας παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Επιστρέφει την έκδοση της εφαρμογής. |
| [getNameOfApplication()](#getNameOfApplication--) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [getCompany()](#getCompany--) | Επιστρέφει ή ορίζει την ιδιότητα της εταιρείας. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα της εταιρείας. |
| [getManager()](#getManager--) | Επιστρέφει ή ορίζει την ιδιότητα του διαχειριστή. |
| [setManager(String value)](#setManager-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα του διαχειριστή. |
| [getPresentationFormat()](#getPresentationFormat--) | Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. |
| [getSharedDoc()](#getSharedDoc--) | Καθορίζει εάν η παρουσίαση είναι κοινή μεταξύ πολλών χρηστών. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Καθορίζει εάν η παρουσίαση είναι κοινή μεταξύ πολλών χρηστών. |
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
| [getLastSavedTime()](#getLastSavedTime--) | Επιστρέφει την ημερομηνία της τελευταίας τροποποίησης μιας παρουσίασης. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Επιστρέφει την ημερομηνία της τελευταίας τροποποίησης μιας παρουσίασης. |
| [getLastPrinted()](#getLastPrinted--) | Επιστρέφει την ημερομηνία που η παρουσίαση εκτυπώθηκε τελευταία φορά. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Επιστρέφει την ημερομηνία που η παρουσίαση εκτυπώθηκε τελευταία φορά. |
| [getLastSavedBy()](#getLastSavedBy--) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που μετέβη τη παρουσίαση. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που μετέβη τη παρουσίαση. |
| [getRevisionNumber()](#getRevisionNumber--) | Επιστρέφει ή ορίζει τον αριθμό έκδοσης της παρουσίασης. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Επιστρέφει ή ορίζει τον αριθμό έκδοσης της παρουσίασης. |
| [getContentStatus()](#getContentStatus--) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [getContentType()](#getContentType--) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Επιστρέφει ή ορίζει την ιδιότητα HyperlinkBase του εγγράφου. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα HyperlinkBase του εγγράφου. |
| [getScaleCrop()](#getScaleCrop--) | Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Δείχνει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Δείχνει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Καθορίζει ότι ένας ή περισσότεροι υπερσύνδεσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [getSlides()](#getSlides--) | Καθορίζει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getHiddenSlides()](#getHiddenSlides--) | Καθορίζει τον αριθμό κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getNotes()](#getNotes--) | Καθορίζει τον αριθμό διαφανειών σε μια παρουσίαση που περιέχει σημειώσεις. |
| [getParagraphs()](#getParagraphs--) | Καθορίζει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο, εάν είναι εφαρμόσιμο. |
| [getWords()](#getWords--) | Καθορίζει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. |
| [getMultimediaClips()](#getMultimediaClips--) | Καθορίζει τον συνολικό αριθμό ηχητικών ή βίντεο κλιπ που υπάρχουν στο έγγραφο. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. |
| [getHeadingPairs()](#getHeadingPairs--) | Δείχνει τη ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό τμημάτων σε κάθε ομάδα. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχει πραγματικά μια συλλογή. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Αφαιρεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με συγκεκριμένο όνομα. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. |
| [clearCustomProperties()](#clearCustomProperties--) | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Λαμβάνει μια ονομαστική boolean τιμή από τις προσαρμοσμένες ιδιότητες. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Λαμβάνει μια ονομαστική int τιμή από τις προσαρμοσμένες ιδιότητες. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Λαμβάνει μια ονομαστική DateTime τιμή από τις προσαρμοσμένες ιδιότητες. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Λαμβάνει μια ονομαστική string τιμή από τις προσαρμοσμένες ιδιότητες. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Λαμβάνει μια ονομαστική float τιμή από τις προσαρμοσμένες ιδιότητες. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Λαμβάνει μια ονομαστική double τιμή από τις προσαρμοσμένες ιδιότητες. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Ορίζει μια ονομαστική boolean προσαρμοσμένη ιδιότητα. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Ορίζει μια ονομαστική int προσαρμοσμένη ιδιότητα. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Ορίζει μια ονομαστική DateTime προσαρμοσμένη ιδιότητα. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Ορίζει μια ονομαστική string προσαρμοσμένη ιδιότητα. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Ορίζει μια ονομαστική float προσαρμοσμένη ιδιότητα. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Ορίζει μια ονομαστική double προσαρμοσμένη ιδιότητα. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Λαμβάνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Επιστρέφει την έκδοση της εφαρμογής. Μόνο ανάγνωση String.

--------------------

Το περιεχόμενο αυτού του στοιχείου πρέπει να είναι της μορφής XX.YYYY, όπου X και Y αντιπροσωπεύουν αριθμητικές τιμές· διαφορετικά, το έγγραφο θεωρείται μη συμβατό. Το Aspose.Slides παρουσιάζει την έκδοσή του στη μορφή XX.YY.ZZ, όπου: XX - κύρια έκδοση YY - δευτερεύουσα έκδοση ZZ - έκδοση διορθώματος. Για παράδειγμα, η τιμή 23.0105 σημαίνει την έκδοση Aspose.Slides 23.1.5.

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

Επιστρέφει ή ορίζει την ιδιότητα της εταιρείας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα της εταιρείας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Επιστρέφει ή ορίζει την ιδιότητα του διαχειριστή. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα του διαχειριστή. Ανάγνωση/εγγραφή String.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**  
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Καθορίζει εάν η παρουσίαση είναι κοινή μεταξύ πολλών χρηστών. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Καθορίζει εάν η παρουσίαση είναι κοινή μεταξύ πολλών χρηστών. Ανάγνωση/εγγραφή boolean.

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
...
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC.P Μόνο για ανάγνωση σε περίπτωση Presentation.DocumentProperties (επειδή θα ενημερωθεί εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του παραδείγματος DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Επιστρέφει:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. Οι τιμές είναι σε UTC.P Μόνο για ανάγνωση σε περίπτωση Presentation.DocumentProperties (επειδή θα ενημερωθεί εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του παραδείγματος DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Παράμετροι:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Δείχνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για ενεργοποίηση κλιμάκωσης της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Ορίστε το σε **false** για ενεργοποίηση περικοπής της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Δείχνει τη λειτουργία προβολής της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για ενεργοποίηση κλιμάκωσης της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Ορίστε το σε **false** για ενεργοποίηση περικοπής της μικρογραφίας ώστε να εμφανίζονται μόνο τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Δείχνει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε το σε **true** για ένδειξη ότι οι υπερσυνδέσεις είναι ενημερωμένες. Ορίστε το σε **false** για ένδειξη ότι οι υπερσυνδέσεις είναι παλαιότερες. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Δείχνει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε το σε **true** για ένδειξη ότι οι υπερσυνδέσεις είναι ενημερωμένες. Ορίστε το σε **false** για ένδειξη ότι οι υπερσυνδέσεις είναι παλαιότερες. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Καθορίζει ότι μια ή περισσότερες υπερσυνδέσεις σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που ανοίγει το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσεων με τις νέες υπερσυνδέσεις που ορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Καθορίζει ότι μια ή περισσότερες υπερσυνδέσεις σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που ανοίγει το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσεων με τις νέες υπερσυνδέσεις που ορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Καθορίζει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Καθορίζει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Καθορίζει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Καθορίζει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο, εφόσον ισχύει. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Καθορίζει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Καθορίζει τον συνολικό αριθμό ηχητικών ή βίντεο κλιπ που υπάρχουν στο έγγραφο. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. Αυτά τα τμήματα δεν είναι πραγματικά τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις ενοτήτων. Μόνο για ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Δείχνει την ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό τμημάτων σε κάθε ομάδα. Μόνο για ανάγνωση IHeadingPair[].

**Επιστρέφει:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιλαμβάνονται στην συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης μιας προσαρμοσμένης ιδιότητας για λήψη. |

**Επιστρέφει:**
java.lang.String - Όνομα προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Αφαιρέστε μια προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα προσαρμοσμένης ιδιότητας προς αφαίρεση. |

**Επιστρέφει:**
boolean - Επιστρέφει true εάν η ιδιότητα αφαιρέθηκε, false διαφορετικά.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Ελέγξτε την παρουσία μιας προσαρμοσμένης ιδιότητας με ένα συγκεκριμένο όνομα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα προσαρμοσμένης ιδιότητας προς έλεγχο. |

**Επιστρέφει:**
boolean - Επιστρέφει true εάν η ιδιότητα υπάρχει, false διαφορετικά.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. Ανάγνωση/εγγραφή Object.

--------------------

Η τιμή μπορεί να είναι **int**, **float**, **double**, **String**, **boolean** ή **Date**.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Επιστρέφει:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με ένα συγκεκριμένο όνομα. Ανάγνωση/εγγραφή Object.

--------------------

Η τιμή μπορεί να είναι **int**, **float**, **double**, **String**, **boolean** ή **Date**.

**Παράμετροι:**
| Parameter | Type | Description |
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

Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις builtIn ιδιότητες.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Λαμβάνει μια τιμή boolean από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας για λήψη |
| value | boolean[] | Τιμή προσαρμοσμένης ιδιότητας |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Λαμβάνει μια τιμή ακέραιου από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας για λήψη |
| value | int[] | Τιμή προσαρμοσμένης ιδιότητας |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Λαμβάνει μια τιμή DateTime από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας για λήψη |
| value | java.util.Date[] | Τιμή προσαρμοσμένης ιδιότητας |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Λαμβάνει μια τιμή συμβολοακολουθίας από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας για λήψη |
| value | java.lang.String[] | Τιμή προσαρμοσμένης ιδιότητας |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Λαμβάνει μια τιμή float από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας για λήψη |
| value | float[] | Τιμή προσαρμοσμένης ιδιότητας |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Λαμβάνει μια τιμή double από τις προσαρμοσμένες ιδιότητες.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |

| όνομα | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας προς λήψη. |
| τιμή | double[] | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | boolean | Custom property value |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα ακέραιου τύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | int | Custom property value |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα DateTime.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.util.Date | Custom property value |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα τύπου string.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.lang.String | Custom property value |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα τύπου float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | float | Custom property value |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Ορίζει μια ονομασμένη προσαρμοσμένη ιδιότητα τύπου double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | double | Custom property value |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Αποκτά ένα πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
com.aspose.slides.ISensitivityLabel[]