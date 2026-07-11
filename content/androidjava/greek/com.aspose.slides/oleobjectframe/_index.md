---
title: OleObjectFrame
second_title: Aspose.Slides για Android μέσω Java API
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
>  // Φορτώνει το PPTX σε αντικείμενο παρουσίασης
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Προσπελάζει την πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Κάνει cast το σχήμα σε OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Διαβάζει το OLE Object και το γράφει στο δίσκο
>      if (oleObjectFrame != null) {
>          // Λαμβάνει δεδομένα ενσωματωμένου αρχείου
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Λαμβάνει την επέκταση του ενσωματωμένου αρχείου
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Δημιουργεί ένα μονοπάτι για αποθήκευση του εξαγόμενου αρχείου
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Αποθηκεύει τα εξαγόμενα δεδομένα
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Επιστρέφει ή θέτει τον τίτλο του εικονιδίου OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Επιστρέφει ή θέτει τον τίτλο του εικονιδίου OleObject. |
| [getObjectName()](#getObjectName--) | Επιστρέφει ή θέτει το όνομα ενός αντικειμένου. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Επιστρέφει ή θέτει το όνομα ενός αντικειμένου. |
| [getObjectProgId()](#getObjectProgId--) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [getLinkFileName()](#getLinkFileName--) | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει κενή συμβολοσειρά. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedData()](#getEmbeddedData--) | Ανακτά ή θέτει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Θέτει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [isObjectIcon()](#isObjectIcon--) | Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. |
| [isObjectLink()](#isObjectLink--) | Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. |

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

Επιστρέφει ή θέτει τον τίτλο του εικονιδίου OleObject. Ανάγνωση/Εγγραφή String.

--------------------

Όταν IsObjectIcon == false, αυτή η τιμή παραβλέπεται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole.

**Επιστρέφει:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Επιστρέφει ή θέτει τον τίτλο του εικονιδίου OleObject. Ανάγνωση/Εγγραφή String.

--------------------

Όταν IsObjectIcon == false, αυτή η τιμή παραβλέπεται. Η συμβολοσειρά μπορεί να περικοπεί ανάλογα με το μέγεθος του εικονιδίου Ole.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Επιστρέφει ή θέτει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Επιστρέφει ή θέτει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String.

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

Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει κενή συμβολοσειρά. Μόνο για ανάγνωση String.

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

Σε παρουσιάσεις Ppt, ορισμένοι σύνδεσμοι Ole αντικειμένων μπορεί να έχουν σχετική αναπαράσταση.

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

Ανακτά ή θέτει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Ανάγνωση/Εγγραφή [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Επιστρέφει:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Θέτει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και θέτει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή  boolean .

**Επιστρέφει:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Καθορίζει αν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Καθορίζει αν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο για ανάγνωση  boolean .

**Επιστρέφει:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. Ανάγνωση/Εγγραφή  boolean .

**Επιστρέφει:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Καθορίζει αν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. Ανάγνωση/Εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |