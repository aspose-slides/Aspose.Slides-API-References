---
title: GeometryShape
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/geometryshape/
---
## GeometryShape κλάση

Αντιπροσωπεύει την γονική κλάση για όλα τα γεωμετρικά σχήματα.

### createShapeElements {#createShapeElements}

| Όνομα | Περιγραφή |
| --- | --- |
| createShapeElements () | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |

**Επιστρέφει:**
[ShapeElement](../shapeelement)

---

### getAdjustments {#getAdjustments}

| Όνομα | Περιγραφή |
| --- | --- |
| getAdjustments () | Επιστρέφει μια συλλογή των τιμών ρυθμίσεων του σχήματος. Μόνο-ανάγνωση IAdjustValueCollection. |

**Επιστρέφει:**
[AdjustValueCollection](../adjustvaluecollection)

---

### getGeometryPaths {#getGeometryPaths}

| Όνομα | Περιγραφή |
| --- | --- |
| getGeometryPaths () | Επιστρέφει ένα αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. |

**Επιστρέφει:**
[GeometryPath](../geometrypath)

---

### getShapeStyle {#getShapeStyle}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeStyle () | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο-ανάγνωση IShapeStyle. |

**Επιστρέφει:**
[ShapeStyle](../shapestyle)

---

### getShapeType {#getShapeType}

| Όνομα | Περιγραφή |
| --- | --- |
| getShapeType () | Επιστρέφει ή ορίζει τον προεπιλεγμένο τύπο γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές ρυθμίσεων θα επανέλθουν στις προεπιλεγμένες τιμές τους. Ανάγνωση/εγγραφή ShapeType. |

**Επιστρέφει:**
int

---

### setGeometryPath {#setGeometryPath}

| Όνομα | Περιγραφή |
| --- | --- |
| setGeometryPath ([GeometryPath](../geometrypath)) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο IGeometryPath. Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType( #getShapeType/ #setShapeType(int))) σε ShapeType#Custom. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryPath | [GeometryPath](../geometrypath) | Διαδρομή γεωμετρίας |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Βρέθηκε κενή διαδρομή |

---

### setGeometryPaths {#setGeometryPaths}

| Όνομα | Περιγραφή |
| --- | --- |
| setGeometryPaths (com.aspose.slides.IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα IGeometryPath. Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType( #getShapeType/ #setShapeType(int))) σε ShapeType#Custom. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryPaths | com.aspose.slides.IGeometryPath[] | Πίνακας διαδρομών γεωμετρίας |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Κενή διαδρομή |

---

### setShapeType {#setShapeType}

| Όνομα | Περιγραφή |
| --- | --- |
| setShapeType (int) | Επιστρέφει ή ορίζει τον προεπιλεγμένο τύπο γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές ρυθμίσεων θα επανέλθουν στις προεπιλεγμένες τιμές τους. Ανάγνωση/εγγραφή ShapeType. |

**Επιστρέφει:**
void

---