---
title: IControl
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει έναν έλεγχο ActiveX.
type: docs
url: /el/com.aspose.slides/icontrol/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Αντιπροσωπεύει ένα ActiveX control.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει το όνομα αυτού του ελέγχου. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα αυτού του ελέγχου. |
| [getClassId()](#getClassId--) | Λαμβάνει το αναγνωριστικό κλάσης αυτού του ελέγχου. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γέμισης εικόνας ControlEx. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. |
| [getProperties()](#getProperties--) | Επιστρέφει μια συλλογή ιδιοτήτων ActiveX. |
| [getPersistence()](#getPersistence--) | Λαμβάνει τη μέθοδο που χρησιμοποιείται για την αποθήκευση ιδιοτήτων του ActiveX control. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Καθορίζει τη διατήρηση ενός ActiveX control όταν η μέθοδος που χρησιμοποιείται για τη διατήρηση είναι είτε PersistStream, PersistStreamInit ή PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει το όνομα αυτού του ελέγχου. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Επιστρέφει το όνομα αυτού του ελέγχου. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Λαμβάνει το αναγνωριστικό κλάσης αυτού του ελέγχου. Μόνο για ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Επιστρέφει το αντικείμενο ιδιοτήτων γέμισης εικόνας ControlEx. Μόνο για ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/Εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/Εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Επιστρέφει μια συλλογή ιδιοτήτων ActiveX. Μόνο για ανάγνωση [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Επιστρέφει:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Λαμβάνει τη μέθοδο που χρησιμοποιείται για την αποθήκευση ιδιοτήτων του ActiveX control. Μόνο για ανάγνωση [PersistenceType](../../com.aspose.slides/persistencetype).

**Επιστρέφει:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Καθορίζει τη διατήρηση ενός ActiveX control όταν η μέθοδος που χρησιμοποιείται για τη διατήρηση είναι είτε PersistStream, PersistStreamInit ή PersistStorage.

**Επιστρέφει:**
byte[]