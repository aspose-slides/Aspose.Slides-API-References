---
title: DocumentProperties
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά τις ιδιότητες μιας παρουσίασης.
type: docs
url: /el/com.aspose.slides/documentproperties/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Αναπαριστά τις ιδιότητες μιας παρουσίασης.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Δημιουργήστε ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει την παρουσίαση
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Δημιουργήστε μια αναφορά στο αντικείμενο IDocumentProperties που συνδέεται με την Παρουσίαση
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
>  // Δημιουργήστε ένα αντικείμενο της κλάσης Presentation που αντιπροσωπεύει την Παρουσίαση
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Δημιουργήστε μια αναφορά στο αντικείμενο IDocumentProperties που συνδέεται με την Παρουσίαση
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Ορίστε τις ενσωματωμένες ιδιότητες
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Αποθηκεύστε την παρουσίασή σας σε αρχείο
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initializes new instance of class [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Returns the app version. |
| [getNameOfApplication()](#getNameOfApplication--) | Returns or sets the name of the application. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Returns or sets the name of the application. |
| [getCompany()](#getCompany--) | Returns or sets the company property. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Returns or sets the company property. |
| [getManager()](#getManager--) | Returns or sets the manager property. |
| [setManager(String value)](#setManager-java.lang.String-) | Returns or sets the manager property. |
| [getPresentationFormat()](#getPresentationFormat--) | Returns or sets the intended format of a presentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Returns or sets the intended format of a presentation. |
| [getSharedDoc()](#getSharedDoc--) | Determines whether the presentation is shared between multiple people. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Determines whether the presentation is shared between multiple people. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Returns or sets the template of a application. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Returns or sets the template of a application. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Total editing time of a presentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Total editing time of a presentation. |
| [getTitle()](#getTitle--) | Returns or sets the title of a presentation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Returns or sets the title of a presentation. |
| [getSubject()](#getSubject--) | Returns or sets the subject of a presentation. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Returns or sets the subject of a presentation. |
| [getAuthor()](#getAuthor--) | Returns or sets the author of a presentation. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Returns or sets the author of a presentation. |
| [getKeywords()](#getKeywords--) | Returns or sets the keywords of a presentation. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Returns or sets the keywords of a presentation. |
| [getComments()](#getComments--) | Returns or sets the comments of a presentation. |
| [setComments(String value)](#setComments-java.lang.String-) | Returns or sets the comments of a presentation. |
| [getCategory()](#getCategory--) | Returns or sets the category of a presentation. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Returns or sets the category of a presentation. |
| [getCreatedTime()](#getCreatedTime--) | Returns the date a presentation was created. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns the date a presentation was created. |
| [getLastSavedTime()](#getLastSavedTime--) | Returns the date a presentation was last modified. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Returns the date a presentation was last modified. |
| [getLastPrinted()](#getLastPrinted--) | Returns the date when a presentation was printed last time. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Returns the date when a presentation was printed last time. |
| [getLastSavedBy()](#getLastSavedBy--) | Returns or sets the name of a last person who modified a presentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Returns or sets the name of a last person who modified a presentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Returns or sets the presentation revision number. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Returns or sets the presentation revision number. |
| [getContentStatus()](#getContentStatus--) | Returns or sets the content status of a presentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Returns or sets the content status of a presentation. |
| [getContentType()](#getContentType--) | Returns or sets the content type of a presentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Returns or sets the content type of a presentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Returns or sets the HyperlinkBase document property. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Returns or sets the HyperlinkBase document property. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Returns the number of custom properties actually contained in a collection. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Return a custom property name at the specified index. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Remove a custom property associated with a specified name. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Check presents of a custom property with a specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets the custom property associated with a specified name. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Returns or sets the custom property associated with a specified name. |
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
| [clearCustomProperties()](#clearCustomProperties--) | Removes all custom properties. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Clears and sets default values for all builtIn properties. |
| [getScaleCrop()](#getScaleCrop--) | Indicates the display mode of the document thumbnail. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indicates the display mode of the document thumbnail. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indicates whether hyperlinks in a document are up-to-date. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indicates whether hyperlinks in a document are up-to-date. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Specifies that one or more hyperlinks in this part were updated exclusively in this part by a producer. |
| [getSlides()](#getSlides--) | Returns the total number of slides in a presentation document. |
| [getHiddenSlides()](#getHiddenSlides--) | Returns the number of hidden slides in a presentation document. |
| [getNotes()](#getNotes--) | Returns the number of slides in a presentation containing notes. |
| [getParagraphs()](#getParagraphs--) | Returns the total number of paragraphs found in a document if applicable. |
| [getWords()](#getWords--) | Returns the total number of words contained in a document. |
| [getMultimediaClips()](#getMultimediaClips--) | Returns the total number of sound or video clips that are present in the document. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Specifies the title of each document part. |
| [getHeadingPairs()](#getHeadingPairs--) | Indicates the grouping of document parts and the number of parts in each group. |
| [deepClone()](#deepClone--) | Clones current object |
| [cloneT()](#cloneT--) | Clones current object |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Επιστρέφει την έκδοση της εφαρμογής. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Επιστρέφει ή ορίζει το όνομα της εφαρμογής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα εταιρείας. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα διαχειριστή. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Επιστρέφει ή ορίζει το προτιμώμενο φορμάτ μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Επιστρέφει ή ορίζει το προτιμώμενο φορμάτ μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Καθορίζει αν η παρουσίαση είναι κοινόχρηστη από πολλούς χρήστες. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Καθορίζει αν η παρουσίαση είναι κοινόχρηστη από πολλούς χρήστες. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Επιστρέφει ή ορίζει το πρότυπο μιας εφαρμογής. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Συνολικός χρόνος επεξεργασίας μιας παρουσίασης. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Επιστρέφει ή ορίζει το θέμα μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Επιστρέφει ή ορίζει τον δημιουργό μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Επιστρέφει ή ορίζει τις λέξεις-κλειδιά μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Επιστρέφει ή ορίζει τα σχόλια μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Επιστρέφει ή ορίζει την κατηγορία μιας παρουσίασης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Επιστρέφει την ημερομηνία δημιουργίας της παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/Εγγραφή java.util.Date.

**Επιστρέφει:**  
java.util.Date  
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}  
```
public final void setCreatedTime(Date value)
```

Επιστρέφει την ημερομηνία δημιουργίας της παρουσίασης. Οι τιμές είναι σε UTC. Ανάγνωση/Εγγραφή java.util.Date.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}  
```
public final Date getLastSavedTime()
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης της παρουσίασης. Οι τιμές είναι σε UTC. Μόνο ανάγνωση στην περίπτωση Presentation.DocumentProperties (επειδή θα ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του αντικειμένου DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Επιστρέφει:**  
java.util.Date  
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}  
```
public final void setLastSavedTime(Date value)
```

Επιστρέφει την ημερομηνία τελευταίας τροποποίησης της παρουσίασης. Οι τιμές είναι σε UTC. Μόνο ανάγνωση στην περίπτωση Presentation.DocumentProperties (επειδή θα ενημερώνεται εσωτερικά κατά τη διαδικασία αποθήκευσης του αντικειμένου IPresentation). Μπορεί να αλλάξει μέσω του αντικειμένου DocumentProperties που επιστρέφεται από τη μέθοδο [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Δείτε το παράδειγμα στη σύνοψη της μεθόδου [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}  
```
public final Date getLastPrinted()
```

Επιστρέφει την ημερομηνία κατά την οποία η παρουσίαση εκτυπώθηκε τελευταία φορά. Ανάγνωση/Εγγραφή java.util.Date.

**Επιστρέφει:**  
java.util.Date  
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}  
```
public final void setLastPrinted(Date value)
```

Επιστρέφει την ημερομηνία κατά την οποία η παρουσίαση εκτυπώθηκε τελευταία φορά. Ανάγνωση/Εγγραφή java.util.Date.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}  
```
public final String getLastSavedBy()
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String  
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}  
```
public final void setLastSavedBy(String value)
```

Επιστρέφει ή ορίζει το όνομα του τελευταίου ατόμου που τροποποίησε την παρουσίαση. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}  
```
public final int getRevisionNumber()
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**  
int  
### setRevisionNumber(int value) {#setRevisionNumber-int-}  
```
public final void setRevisionNumber(int value)
```

Επιστρέφει ή ορίζει τον αριθμό αναθεώρησης της παρουσίασης. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}  
```
public final String getContentStatus()
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String  
### setContentStatus(String value) {#setContentStatus-java.lang.String-}  
```
public final void setContentStatus(String value)
```

Επιστρέφει ή ορίζει την κατάσταση περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}  
```
public final String getContentType()
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String  
### setContentType(String value) {#setContentType-java.lang.String-}  
```
public final void setContentType(String value)
```

Επιστρέφει ή ορίζει τον τύπο περιεχομένου μιας παρουσίασης. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}  
```
public final String getHyperlinkBase()
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**  
java.lang.String  
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}  
```
public final void setHyperlinkBase(String value)
```

Επιστρέφει ή ορίζει την ιδιότητα εγγράφου HyperlinkBase. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}  
```
public final int getCountOfCustomProperties()
```

Επιστρέφει τον αριθμό των προσαρμοσμένων ιδιοτήτων που περιέχονται πραγματικά σε μια συλλογή. Μόνο ανάγνωση int.

**Επιστρέφει:**  
int  
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}  
```
public final String getCustomPropertyName(int index)
```

Επιστρέφει ένα όνομα προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν της προσαρμοσμένης ιδιότητας που θα ληφθεί. |

**Επιστρέφει:**  
java.lang.String - Όνομα προσαρμοσμένης ιδιότητας στο συγκεκριμένο δείκτη.  
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}  
```
public final boolean removeCustomProperty(String name)
```

Καταργεί μια προσαρμοσμένη ιδιότητα που συνδέεται με το συγκεκριμένο όνομα.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα καταργηθεί. |

**Επιστρέφει:**  
boolean - Επιστρέφει true εάν μια ιδιότητα αφαιρέθηκε, false διαφορετικά.  
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}  
```
public final boolean containsCustomProperty(String name)
```

Ελέγχει την παρουσία μιας προσαρμοσμένης ιδιότητας με το συγκεκριμένο όνομα.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ελεγχθεί. |

**Επιστρέφει:**  
boolean - Επιστρέφει true εάν η ιδιότητα υπάρχει, false διαφορετικά.  
### get_Item(String name) {#get-Item-java.lang.String-}  
```
public final Object get_Item(String name)
```

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που συνδέεται με το συγκεκριμένο όνομα. Ανάγνωση/Εγγραφή Object.

  
Η τιμή μπορεί να είναι **int**, **float**, **String**, **boolean** ή **Date**.

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

Επιστρέφει ή ορίζει την προσαρμοσμένη ιδιότητα που συνδέεται με το συγκεκριμένο όνομα. Ανάγνωση/Εγγραφή Object.

  
Η τιμή μπορεί να είναι **int**, **float**, **String**, **boolean** ή **Date**.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}  
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Λαμβάνει την τιμή boolean μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | boolean[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}  
```
public final void getCustomPropertyValue(String name, int[] value)
```

Λαμβάνει την τιμή ακέραιου (int) μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | int[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}  
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Λαμβάνει την τιμή DateTime μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | java.util.Date[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}  
```
public final void getCustomPropertyValue(String name, String[] value)
```

Λαμβάνει την τιμή συμβολοσειράς μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | java.lang.String[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}  
```
public final void getCustomPropertyValue(String name, float[] value)
```

Λαμβάνει την τιμή float μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί |
| value | float[] | Τιμή προσαρμοσμένης ιδιότητας |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}  
```
public final void getCustomPropertyValue(String name, double[] value)
```

Λαμβάνει την τιμή double μιας ονομασμένης προσαρμοσμένης ιδιότητας.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ληφθεί. |
| value | double[] | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}  
```
public final void setCustomPropertyValue(String name, boolean value)
```

Ορίζει μια ονομασμένη boolean προσαρμοσμένη ιδιότητα.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | boolean | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}  
```
public final void setCustomPropertyValue(String name, int value)
```

Ορίζει μια ονομασμένη ακέραια (int) προσαρμοσμένη ιδιότητα.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | int | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}  
```
public final void setCustomPropertyValue(String name, Date value)
```

Ορίζει μια ονομασμένη DateTime προσαρμοσμένη ιδιότητα.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | java.util.Date | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}  
```
public final void setCustomPropertyValue(String name, String value)
```

Ορίζει μια ονομασμένη ιδιότητα τύπου String.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | java.lang.String | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}  
```
public final void setCustomPropertyValue(String name, float value)
```

Ορίζει μια ονομασμένη ιδιότητα τύπου float.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | float | Τιμή προσαρμοσμένης ιδιότητας |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}  
```
public final void setCustomPropertyValue(String name, double value)
```

Ορίζει μια ονομασμένη ιδιότητα τύπου double.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Όνομα της προσαρμοσμένης ιδιότητας που θα ορισθεί |
| value | double | Τιμή προσαρμοσμένης ιδιότητας |

### clearCustomProperties() {#clearCustomProperties--}  
```
public final void clearCustomProperties()
```

Καταργεί όλες τις προσαρμοσμένες ιδιότητες.

### getSensitivityLabels() {#getSensitivityLabels--}  
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Λαμβάνει έναν πίνακα ετικετών ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Λάβετε τις ετικέτες ευαισθησίας από τις προσαρμοσμένες ιδιότητες εγγράφου
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Προσθέστε την ετικέτα στη συλλογή
>          // Εδώ μπορείτε να προσθέσετε έναν έλεγχο για την εγκυρότητα των πληροφοριών της ετικέτας (η ετικέτα είναι διαθέσιμη, κ.λπ.)
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
public final void clearBuiltInProperties()
```

Καθαρίζει και ορίζει τις προεπιλεγμένες τιμές για όλες τις ενσωματωμένες ιδιότητες.

### getScaleCrop() {#getScaleCrop--}  
```
public final boolean getScaleCrop()
```

Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιηθεί η κλιμάκωση της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Ορίστε το σε **false** για να ενεργοποιηθεί η περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τα τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**  
boolean  
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}  
```
public final void setScaleCrop(boolean value)
```

Δείχνει τη λειτουργία εμφάνισης της μικρογραφίας του εγγράφου. Ορίστε αυτό το στοιχείο σε **true** για να ενεργοποιηθεί η κλιμάκωση της μικρογραφίας ώστε να ταιριάζει στην οθόνη. Ορίστε το σε **false** για να ενεργοποιηθεί η περικοπή της μικρογραφίας ώστε να εμφανίζονται μόνο τα τμήματα που ταιριάζουν στην οθόνη. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}  
```
public final boolean getLinksUpToDate()
```

Δείχνει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσυνδέσεις έχουν ενημερωθεί. Ορίστε το σε **false** για να υποδείξετε ότι οι υπερσυνδέσεις είναι παλαιές. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**  
boolean  
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}  
```
public final void setLinksUpToDate(boolean value)
```
Δεικνύει εάν οι υπερσυνδέσεις σε ένα έγγραφο είναι ενημερωμένες. Ορίστε αυτό το στοιχείο σε **true** για να υποδείξετε ότι οι υπερσυνδέσεις είναι ενημερωμένες. Ορίστε αυτό το στοιχείο σε **false** για να υποδείξετε ότι οι υπερσυνδέσεις είναι παλαιές. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Καθορίζει ότι μία ή περισσότερες υπερσυνδέσεις σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσεων με τις νέες υπερσυνδέσεις που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Καθορίζει ότι μία ή περισσότερες υπερσυνδέσεις σε αυτό το τμήμα ενημερώθηκαν αποκλειστικά σε αυτό το τμήμα από έναν παραγωγό. Ο επόμενος παραγωγός που θα ανοίξει αυτό το έγγραφο θα ενημερώσει τις σχέσεις υπερσυνδέσεων με τις νέες υπερσυνδέσεις που καθορίζονται σε αυτό το τμήμα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Επιστρέφει τον συνολικό αριθμό διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Επιστρέφει τον αριθμό κρυφών διαφανειών σε ένα έγγραφο παρουσίασης. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Επιστρέφει τον αριθμό διαφανειών σε μια παρουσίαση που περιέχουν σημειώσεις. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Επιστρέφει τον συνολικό αριθμό παραγράφων που βρέθηκαν σε ένα έγγραφο εάν είναι εφαρμόσιμο. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Επιστρέφει τον συνολικό αριθμό λέξεων που περιέχονται σε ένα έγγραφο. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Επιστρέφει τον συνολικό αριθμό ηχητικών ή βιντεοαποσπασμάτων που υπάρχουν στο έγγραφο. Μόνο-ανάγνωση int.

**Επιστρέφει:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Καθορίζει τον τίτλο κάθε μέρους του εγγράφου. Αυτά τα μέρη δεν είναι τμήματα εγγράφου αλλά εννοιολογικές αναπαραστάσεις των ενοτήτων του εγγράφου. Μόνο-ανάγνωση String[].

**Επιστρέφει:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Δεικνύει την ομαδοποίηση των μερών του εγγράφου και τον αριθμό των μερών σε κάθε ομάδα. Μόνο-ανάγνωση IHeadingPair[].

**Επιστρέφει:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final IHeadingPair[] getHeadingPairs()
```

Κλωνοποιεί το τρέχον αντικείμενο

**Επιστρέφει:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Κλωνοποιεί το τρέχον αντικείμενο

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone