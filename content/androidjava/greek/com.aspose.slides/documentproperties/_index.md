---
title: DocumentProperties
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά τις ιδιότητες μιας παρουσίασης.
type: docs
url: /el/com.aspose.slides/documentproperties/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Αναπαριστά τις ιδιότητες μιας παρουσίασης.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Δημιουργήστε μια παρουσία της κλάσης Presentation που αντιπροσωπεύει την παρουσίαση
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Δημιουργήστε μια αναφορά στο αντικείμενο IDocumentProperties που σχετίζεται με την Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Εμφανίστε τις ενσωματωμένες ιδιότητες
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Δημιουργήστε μια παρουσία της κλάσης Presentation που αντιπροσωπεύει την Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Δημιουργήστε μια αναφορά στο αντικείμενο IDocumentProperties που σχετίζεται με την Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Ορίστε τις ενσωματωμένες ιδιότητες
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Αποθηκεύστε την παρουσίασή σας σε ένα αρχείο
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Δημιουργεί νέο στιγμιότυπο της κλάσης [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Επιστρέφει την έκδοση της εφαρμογής. |
| [getNameOfApplication()](#getNameOfApplication--) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα της εφαρμογής. |
| [getCompany()](#getCompany--) | Επιστρέφει ή ορίζει την ιδιότητα company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα company. |
| [getManager()](#getManager--) | Επιστρέφει ή ορίζει την ιδιότητα manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα manager. |
| [getPresentationFormat()](#getPresentationFormat--) | Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. |
| [getSharedDoc()](#getSharedDoc--) | Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών χρηστών. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών χρηστών. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. |
| [getTitle()](#getTitle--) | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. |
| [getSubject()](#getSubject--) | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. |
| [getAuthor()](#getAuthor--) | Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. |
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
| [getLastPrinted()](#getLastPrinted--) | Επιστρέφει την ημερομηνία εκτύπωσης της παρουσίασης την τελευταία φορά. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Επιστρέφει την ημερομηνία εκτύπωσης της παρουσίασης την τελευταία φορά. |
| [getLastSavedBy()](#getLastSavedBy--) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. |
| [getRevisionNumber()](#getRevisionNumber--) | Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. |
| [getContentStatus()](#getContentStatus--) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. |
| [getContentType()](#getContentType--) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται στην συλλογή. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο ευρετήριο. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Καταργεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με το συγκεκριμένο όνομα. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Ορίζει μια προσαρμοσμένη boolean ιδιότητα με όνομα. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Ορίζει μια προσαρμοσμένη ιδιότητα τύπου integer με όνομα. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Ορίζει μια προσαρμοσμένη ιδιότητα τύπου DateTime με όνομα. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Ορίζει μια προσαρμοσμένη ιδιότητα τύπου string με όνομα. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Ορίζει μια προσαρμοσμένη ιδιότητα τύπου float με όνομα. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Ορίζει μια προσαρμοσμένη ιδιότητα τύπου double με όνομα. |
| [clearCustomProperties()](#clearCustomProperties--) | Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Παίρνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες. |
| [getScaleCrop()](#getScaleCrop--) | Καθορίζει τη λειτουργία εμφάνισης της μικρογραφίας εγγράφου. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Καθορίζει τη λειτουργία εμφάνισης της μικρογραφίας εγγράφου. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Καθορίζει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Καθορίζει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Καθορίζει ότι ένας ή περισσότεροι υπερσυνδέσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Καθορίζει ότι ένας ή περισσότεροι υπερσυνδέσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. |
| [getSlides()](#getSlides--) | Επιστρέφει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getHiddenSlides()](#getHiddenSlides--) | Επιστρέφει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. |
| [getNotes()](#getNotes--) | Επιστρέφει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. |
| [getParagraphs()](#getParagraphs--) | Επιστρέφει το συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο αν είναι εφαρμόσιμο. |
| [getWords()](#getWords--) | Επιστρέφει το συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. |
| [getMultimediaClips()](#getMultimediaClips--) | Επιστρέφει το συνολικό αριθμό ηχητικών ή βίντεο κλιπ που υπάρχουν στο έγγραφο. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. |
| [getHeadingPairs()](#getHeadingPairs--) | Καθορίζει τη ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό των τμημάτων σε κάθε ομάδα. |
| [deepClone()](#deepClone--) | Δημιουργεί κλώνο του τρέχοντος αντικειμένου |
| [cloneT()](#cloneT--) | Δημιουργεί κλώνο του τρέχοντος αντικειμένου |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Δημιουργεί νέο στιγμιότυπο της κλάσης [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Επιστρέφει την έκδοση της εφαρμογής. String μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Επιστρέφει ή ορίζει την ιδιότητα company. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα company. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Επιστρέφει ή ορίζει την ιδιότητα manager. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα manager. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Επιστρέφει ή ορίζει τη ζητούμενη μορφή μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών χρηστών. boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Καθορίζει εάν η παρουσίαση είναι κοινόχρηστη μεταξύ πολλών χρηστών. boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. double ανάγνωση/εγγραφή.

**Επιστρέφει:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. double ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public      \*\*The following code snippet is **written** in `java`. It does not do *any* parsing or evaluation. This
  is a dumb **example
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. τιμές σε UTC. java.util.Date ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Επιστρέφει την ημερομηνία δημιουργίας μιας παρουσίασης. τιμές σε UTC. java.util.Date ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. τιμές σε UTC. Μόνο για ανάγνωση στην περίπτωση Presentation.DocumentProperties (επειδή ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω της παρουσίας DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Επιστρέφει:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης μιας παρουσίασης. τιμές σε UTC. Μόνο για ανάγνωση στην περίπτωση Presentation.DocumentProperties (επειδή ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω της παρουσίας DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Επιστρέφει την ημερομηνία εκτύπωσης της παρουσίασης την τελευταία φορά. java.util.Date ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Επιστρέφει την ημερομηνία εκτύπωσης της παρουσίασης την τελευταία φορά. java.util.Date ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε μια παρουσίαση. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. int ανάγνωση/εγγραφή.

**Επιστρέφει:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public   \*\*The  \*\* smiles  \*\*\*\*
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. int ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται στην συλλογή. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Επιστρέφει το όνομα μιας προσαρμοσμένης ιδιότητας στο συγκεκριμένο ευρετήριο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of a custom property to get. |

**Επιστρέφει:**
java.lang.String - Custom property name at the specified index.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Καταργεί μια προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a custom property to remove. |

**Επιστρέφει:**
boolean - Return true if a property was removed, false otherwise.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με το συγκεκριμένο όνομα.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a custom property to check. |

**Επιστρέφει:**
boolean - Return true if property exists, false otherwise.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα. Object ανάγνωση/εγγραφή.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Επιστρέφει:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που σχετίζεται με το συγκεκριμένο όνομα. Object ανάγνωση/εγγραφή.

--------------------

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Gets a named boolean value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | boolean[] | Custom property value |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public  c  in  **\  
```

Gets a named integer value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | int[] | Custom property value |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Gets a named DateTime value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | java.util.Date[] | Custom property value |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Gets a named string value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | java.lang.String[] | Custom property value |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Gets a named float value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get |
| value | float[] | Custom property value |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Gets a named double value from the custom properties.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to get. |
| value | double[] | Custom property value |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Sets a named boolean custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | boolean | Custom property value |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Sets a named integer custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | int | Custom property value |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Sets a named DateTime custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.util.Date | Custom property value |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Sets a named string custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | java.lang.String | Custom property value |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Sets a named float custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | float | Custom property value |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Sets a named double custom property.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the custom property to set |
| value | double | Custom property value |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Αφαιρεί όλες τις προσαρμοσμένες ιδιότητες.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Λάβετε ετικέτες ευαισθησίας από τις προσαρμοσμένες ιδιότητες του εγγράφου
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Προσθέστε την ετικέτα στη συλλογή
>          // Εδώ μπορείτε να προσθέσετε έλεγχο για την εγκυρότητα των πληροφοριών της ετικέτας (η ετικέτα είναι διαθέσιμη, κ.λπ.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public  



The  







“  



  







This  



“  



 



 



 



 



f 







··



........



 



…



```


Καθαρίζει και ορίζει προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Καθορίζει τη λειτουργία εμφάνισης της μικρογραφίας εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για ενεργοποίηση κλιμάκωσης της μικρογραφίας εγγράφου στην εμφάνιση. Ορίστε το σε **false** για ενεργοποίηση περικοπής της μικρογραφίας ώστε να εμφανίζει μόνο τμήματα που ταιριάζουν στην οθόνη. boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Καθορίζει τη λειτουργία εμφάνισης της μικρογραφίας εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για ενεργοποίηση κλιμάκωσης της μικρογραφίας εγγράφου στην εμφάνιση. Ορίστε το σε **false** για ενεργοποίηση περικοπής της μικρογραφίας ώστε να εμφανίζει μόνο τμήματα που ταιριάζουν στην οθόνη. boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Καθορίζει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε αυτό το στοιχείο σε **true** για υποδείξη ότι οι υπερσυνδέσεις είναι ενημερωμένες. Ορίστε το σε **false** για υποδείξη ότι οι υπερσυνδέσεις είναι παρωχημένες. boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

Καθορίζει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε αυτό το στοιχείο σε **true** για υποδείξη ότι οι υπερσυνδέσεις είναι ενημερωμένες. Ορίστε το σε **false** για υποδείξη ότι οι υπερσυνδέσεις είναι παρωχημένες. boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Καθορίζει ότι ένας ή περισσότεροι υπερσυνδέσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Καθορίζει ότι ένας ή περισσότεροι υπερσυνδέσμοι σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```

Επιστρέφει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Επιστρέφει τον αριθμό των κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Επιστρέφει τον αριθμό των διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Επιστρέφει το συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο αν είναι εφαρμόσιμο. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getWords() {#getWords--}
```
public














  

















```

Επιστρέφει το συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Επιστρέφει το συνολικό αριθμό ηχητικών ή βίντεο κλιπ που υπάρχουν στο έγγραφο. int μόνο για ανάγνωση.

**Επιστρέφει:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Καθορίζει τον τίτλο κάθε τμήματος του εγγράφου. These parts are not document parts but conceptual representations of document sections. Read-only String[].

**Επιστρέφει:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public 



  



















  

 

```

Καθορίζει τη ομαδοποίηση των τμημάτων του εγγράφου και τον αριθμό των τμημάτων σε κάθε ομάδα. Read-only IHeadingPair[].

**Επιστρέφει:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Δημιουργεί κλώνο του τρέχοντος αντικειμένου

**Επιστρέφει:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Δημιουργεί κλώνο του τρέχοντος αντικειμένου

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone