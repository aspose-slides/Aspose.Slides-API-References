---
title: IOleObjectFrame
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ioleobjectframe/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. |
| [getObjectName()](#getObjectName--) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. |
| [getEmbeddedData()](#getEmbeddedData--) | Λαμβάνει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| [getObjectProgId()](#getObjectProgId--) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Επιστρέφει το ProgID ενός αντικειμένου. |
| [getLinkFileName()](#getLinkFileName--) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει, αλλιώς επιστρέφει κενή συμβολοσειρά. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| [isObjectIcon()](#isObjectIcon--) | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. |
| [isObjectLink()](#isObjectLink--) | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. |
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


Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Λαμβάνει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Μόνο ανάγνωση [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Επιστρέφει:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE.

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
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και ορίζει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. String ανάγνωση/εγγραφή.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. String ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει, αλλιώς επιστρέφει κενή συμβολοσειρά. Μόνο ανάγνωση String.

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


Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE

**Επιστρέφει:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Boolean μόνο ανάγνωση.

**Επιστρέφει:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. Boolean ανάγνωση/εγγραφή.

**Επιστρέφει:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν ανοίγεται ή εκτυπώνεται η παρουσίαση. Boolean ανάγνωση/εγγραφή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. String ανάγνωση/εγγραφή.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικόπτεται ανάλογα με το μέγεθος του εικονιδίου OLE.

**Επιστρέφει:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. String ανάγνωση/εγγραφή.

--------------------

Όταν IsObjectIcon == false αυτή η τιμή αγνοείται. Η συμβολοσειρά μπορεί να περικόπτεται ανάλογα με το μέγεθος του εικονιδίου OLE.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |