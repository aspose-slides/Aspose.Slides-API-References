---
title: Control
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/control/
---
## Control κλάση

Αντιπροσωπεύει έναν έλεγχο ActiveX.

### getActiveXControlBinary {#getActiveXControlBinary}

| Name | Description |
| --- | --- |
| getActiveXControlBinary () | Καθορίζει τη διατήρηση ενός ελέγχου ActiveX όταν η μέθοδος που χρησιμοποιείται για τη διατήρηση είναι είτε PersistStream, PersistStreamInit ή PersistStorage. |

**Επιστρέφει:**
byte


---

### getClassId {#getClassId}

| Name | Description |
| --- | --- |
| getClassId () | Αποκτά το αναγνωριστικό κλάσης αυτού του ελέγχου. Μόνο για ανάγνωση java.util.UUID. |

**Επιστρέφει:**
UUID


---

### getFrame {#getFrame}

| Name | Description |
| --- | --- |
| getFrame () | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/εγγραφή IShapeFrame. |

**Επιστρέφει:**
[ShapeFrame](../shapeframe)


---

### getName {#getName}

| Name | Description |
| --- | --- |
| getName () | Αποκτά ή ορίζει το όνομα αυτού του ελέγχου. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
String


---

### getPersistence {#getPersistence}

| Name | Description |
| --- | --- |
| getPersistence () | Αποκτά τη μέθοδο που χρησιμοποιείται για την αποθήκευση ιδιοτήτων του ελέγχου ActiveX. Μόνο για ανάγνωση PersistenceType. |

**Επιστρέφει:**
int


---

### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () |  |

**Επιστρέφει:**
[Presentation](../presentation)


---

### getProperties {#getProperties}

| Name | Description |
| --- | --- |
| getProperties () | Επιστρέφει μια συλλογή ιδιοτήτων ActiveX. Μόνο για ανάγνωση IControlPropertiesCollection. Σημείωση: Το Aspose.Slides υποστηρίζει μόνο ιδιότητες ActiveX βασισμένες σε XML. Εάν οι ιδιότητες αποθηκευτούν σε δυαδική μορφή, αυτή η ιδιότητα θα επιστρέψει null. |

**Επιστρέφει:**
[ControlPropertiesCollection](../controlpropertiescollection)


---

### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () |  |

**Επιστρέφει:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---

### getSubstitutePictureFormat {#getSubstitutePictureFormat}

| Name | Description |
| --- | --- |
| getSubstitutePictureFormat () | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας ελέγχου. Μόνο για ανάγνωση IPictureFillFormat. |

**Επιστρέφει:**
[PictureFillFormat](../picturefillformat)


---

### setClassId {#setClassId}

| Name | Description |
| --- | --- |
| setClassId (UUID) | Αποκτά το αναγνωριστικό κλάσης αυτού του ελέγχου. Μόνο για ανάγνωση java.util.UUID. |

**Επιστρέφει:**
void


---

### setFrame {#setFrame}

| Name | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Επιστρέφει ή ορίζει το πλαίσιο του ελέγχου. Ανάγνωση/εγγραφή IShapeFrame. |

**Επιστρέφει:**
void


---

### setName {#setName}

| Name | Description |
| --- | --- |
| setName (String) | Αποκτά ή ορίζει το όνομα αυτού του ελέγχου. Ανάγνωση/εγγραφή String. |

**Επιστρέφει:**
void


---