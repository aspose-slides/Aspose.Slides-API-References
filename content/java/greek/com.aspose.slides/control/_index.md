---
title: Control
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά έναν ActiveX control.
type: docs
url: /el/com.aspose.slides/control/
---
**Κληρονομικότητα:**  
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**  
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)  
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Αναπαριστά έναν ActiveX control.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPersistence()](#getPersistence--) | Λαμβάνει τη μέθοδο που χρησιμοποιείται για την αποθήκευση των ιδιοτήτων του ActiveX control. |
| [getName()](#getName--) | Λαμβάνει ή ορίζει το όνομα αυτού του control. |
| [setName(String value)](#setName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα αυτού του control. |
| [getClassId()](#getClassId--) | Λαμβάνει το class id αυτού του control. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Λαμβάνει το class id αυτού του control. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας Control. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει το πλαίσιο του control. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει το πλαίσιο του control. |
| [getProperties()](#getProperties--) | Επιστρέφει μια συλλογή των ιδιοτήτων του ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Καθορίζει την ανθεκτικότητα ενός ActiveX control όταν η μέθοδος αποθήκευσης είναι είτε PersistStream, PersistStreamInit ή PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Λαμβάνει τη μέθοδο που χρησιμοποιείται για την αποθήκευση των ιδιοτήτων του ActiveX control. Μόνο ανάγνωση [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Χρησιμοποιήστε τη δική σας μέθοδο για τη διαχείριση των ιδιοτήτων ActiveX που αποθηκεύονται στο δυαδικό της αρχείο
>  }
> ```


**Επιστρέφει:**  
int

### getName() {#getName--}
```
public final String getName()
```

Λαμβάνει ή ορίζει το όνομα αυτού του control. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Λαμβάνει ή ορίζει το όνομα αυτού του control. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Λαμβάνει το class id αυτού του control. Μόνο ανάγνωση java.util.UUID.

**Επιστρέφει:**  
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Λαμβάνει το class id αυτού του control. Μόνο ανάγνωση java.util.UUID.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας Control. Μόνο ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει το πλαίσιο του control. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Επιστρέφει:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει το πλαίσιο του control. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Επιστρέφει μια συλλογή των ιδιοτήτων του ActiveX. Μόνο ανάγνωση [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Σημείωση: Το Aspose.Slides υποστηρίζει μόνο ιδιότητες ActiveX βασισμένες σε XML. Εάν οι ιδιότητες αποθηκευτούν σε δυαδική μορφή, αυτή η ιδιότητα θα επιστρέψει null.

**Επιστρέφει:**  
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Καθορίζει την ανθεκτικότητα ενός ActiveX control όταν η μέθοδος αποθήκευσης είναι είτε PersistStream, PersistStreamInit ή PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Χρησιμοποιήστε τη δική σας μέθοδο για τη διαχείριση των ιδιοτήτων ActiveX που αποθηκεύονται στο δυαδικό της αρχείο
>  }
> ```


**Επιστρέφει:**  
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Επιστρέφει τη βασική slide. Μόνο ανάγνωση [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Επιστρέφει:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Επιστρέφει την παρουσίαση. Μόνο ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**  
[IPresentation](../../com.aspose.slides/ipresentation)