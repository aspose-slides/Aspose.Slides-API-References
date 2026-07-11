---
title: IControl
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά έναν έλεγχο ActiveX.
type: docs
url: /el/com.aspose.slides/icontrol/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Αναπαριστά έναν έλεγχο ActiveX.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει το όνομα αυτού του ελέγχου. |
| [setName(String value)](#setName-java.lang.String-) | Επιστρέφει το όνομα αυτού του ελέγχου. |
| [getClassId()](#getClassId--) | Αποκτά το αναγνωριστικό κλάσης αυτού του ελέγχου. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας ControlEx. |
| [getFrame()](#getFrame--) | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. |
| [getProperties()](#getProperties--) | Επιστρέφει μια συλλογή ιδιοτήτων ActiveX. |
| [getPersistence()](#getPersistence--) | Αποκτά τη μέθοδο που χρησιμοποιείται για την αποθήκευση ιδιοτήτων του ελέγχου ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Καθορίζει τη μονιμότητα ενός ελέγχου ActiveX όταν η μέθοδος που χρησιμοποιείται για τη διατήρηση είναι είτε PersistStream, PersistStreamInit ή PersistStorage. |

### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει το όνομα αυτού του ελέγχου. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Επιστρέφει το όνομα αυτού του ελέγχου. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

Αποκτά το αναγνωριστικό κλάσης αυτού του ελέγχου. Μόνο-ανάγνωση java.util.UUID.

**Επιστρέφει:**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας ControlEx. Μόνο-ανάγνωση [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Επιστρέφει:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/εγγραφή [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

Επιστρέφει μια συλλογή ιδιοτήτων ActiveX. Μόνο-ανάγνωση [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Επιστρέφει:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

Αποκτά τη μέθοδο που χρησιμοποιείται για την αποθήκευση ιδιοτήτων του ελέγχου ActiveX. Μόνο-ανάγνωση [PersistenceType](../../com.aspose.slides/persistencetype).

**Επιστρέφει:**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

Καθορίζει τη μονιμότητα ενός ελέγχου ActiveX όταν η μέθοδος που χρησιμοποιείται για τη διατήρηση είναι είτε PersistStream, PersistStreamInit ή PersistStorage.

**Επιστρέφει:**
byte[]