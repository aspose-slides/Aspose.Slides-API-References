---
title: OleObjectFrame
second_title: Aspose.Slides για Java - Αναφορά API
description: Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/oleobjectframe/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Φορτώνει το PPTX σε ένα αντικείμενο παρουσίασης
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Πρόσβαση στην πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Μετατρέπει το σχήμα σε OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Διαβάζει το αντικείμενο OLE και το γράφει στον δίσκο
>      if (oleObjectFrame != null) {
>          // Αποκτά τα δεδομένα ενσωματωμένου αρχείου
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Αποκτά την επέκταση ενσωματωμένου αρχείου
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Δημιουργεί μια διαδρομή για την αποθήκευση του εξαγόμενου αρχείου
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Αποθηκεύει τα εξαγόμενα δεδομένα
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. |
| [getObjectName()](#getObjectName--) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [getObjectProgId()](#getObjectProgId--) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [getLinkFileName()](#getLinkFileName--) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει μια κενή συμβολοσειρά. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedData()](#getEmbeddedData--) | Ανακτά ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [isObjectIcon()](#isObjectIcon--) | Καθορίζει αν ένα αντικείμενο εμφανίζεται ως εικονίδιο. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Καθορίζει αν ένα αντικείμενο εμφανίζεται ως εικονίδιο. |
| [isObjectLink()](#isObjectLink--) | Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/εγγραφή String.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole.

**Επιστρέφει:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/εγγραφή String.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Επιστρέφει το ProgID ενός αντικειμένου. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Επιστρέφει το ProgID ενός αντικειμένου. Μόνο για ανάγνωση String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μικρό όνομα αρχείου. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει μια κενή συμβολοσειρά. Μόνο για ανάγνωση String.

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
public final String getEmbeddedFileLabel()
```

Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE

**Επιστρέφει:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE

**Επιστρέφει:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Ανακτά ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Ανάγνωση/εγγραφή [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Επιστρέφει:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντικατοπτρίζουν τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/εγγραφή boolean .

**Επιστρέφει:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/εγγραφή boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο για ανάγνωση boolean .

**Επιστρέφει:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/εγγραφή boolean .

**Επιστρέφει:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/εγγραφή boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |