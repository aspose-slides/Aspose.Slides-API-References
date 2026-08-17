---
title: IOleObjectFrame
second_title: Aspose.Slides για τη Java API Αναφορά
description: Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ioleobjectframe/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. |
| [getObjectName()](#getObjectName--) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [getEmbeddedData()](#getEmbeddedData--) | Αποκτά πληροφορίες σχετικά με ενσωματωμένα δεδομένα OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Ορίζει πληροφορίες σχετικά με ενσωματωμένα δεδομένα OLE. |
| [getObjectProgId()](#getObjectProgId--) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [getLinkFileName()](#getLinkFileName--) | Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Επιστρέφει το σχετικό μονοπάτι σε ένα συνδεδεμένο αρχείο εάν υπάρχει, διαφορετικά επιστρέφει κενή συμβολοσειρά. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Επιστρέφει το μονοπάτι του ενσωματωμένου αντικειμένου OLE |
| [isObjectIcon()](#isObjectIcon--) | Καθορίζει αν ένα αντικείμενο εμφανίζεται ως εικονίδιο. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Καθορίζει αν ένα αντικείμενο εμφανίζεται ως εικονίδιο. |
| [isObjectLink()](#isObjectLink--) | Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο σε εξωτερικό αρχείο. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγεται ή εκτυπώνεται. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγεται ή εκτυπώνεται. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Αποκτά πληροφορίες σχετικά με ενσωματωμένα δεδομένα OLE. Μόνο ανάγνωση [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Επιστρέφει:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Ορίζει πληροφορίες σχετικά με ενσωματωμένα δεδομένα OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Ενσωματωμένα δεδομένα [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντικατοπτρίζουν τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Επιστρέφει το ProgID ενός αντικειμένου. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Επιστρέφει το ProgID ενός αντικειμένου. Μόνο ανάγνωση String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί σύντομο όνομα αρχείου. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Επιστρέφει το πλήρες μονοπάτι σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Επιστρέφει το σχετικό μονοπάτι σε ένα συνδεδεμένο αρχείο εάν υπάρχει, διαφορετικά επιστρέφει κενή συμβολοσειρά. Μόνο ανάγνωση String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Στις παρουσιάσεις Ppt, ορισμένοι σύνδεσμοι αντικειμένων Ole μπορεί να έχουν σχετική αναπαράσταση.

**Επιστρέφει:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE

**Επιστρέφει:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Επιστρέφει το μονοπάτι του ενσωματωμένου αντικειμένου OLE

**Επιστρέφει:**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο σε εξωτερικό αρχείο. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/Εγγραφή String.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου OLE.

**Επιστρέφει:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/Εγγραφή String.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |