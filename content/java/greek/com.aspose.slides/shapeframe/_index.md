---
title: ShapeFrame
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά τις ιδιότητες των πλαισίων σχήματος.
type: docs
url: /el/com.aspose.slides/shapeframe/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Αναπαριστά τις ιδιότητες του πλαισίου σχήματος.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Δημιουργεί νέες ιδιότητες πλαισίου σχήματος. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getX()](#getX--) | Επιστρέφει τη συντεταγμένη X της επάνω-αριστερής γωνίας ενός πλαισίου. |
| [getY()](#getY--) | Επιστρέφει τη συντεταγμένη Y της επάνω-αριστερής γωνίας ενός πλαισίου. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος ενός πλαισίου. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος ενός πλαισίου. |
| [getRotation()](#getRotation--) | Επιστρέφει τον αριθμό μοιρών κατά τις οποίες ένα πλαίσιο περιστρέφεται γύρω από τον άξονα z. |
| [getCenterX()](#getCenterX--) | Επιστρέφει τη συντεταγμένη X του κέντρου ενός πλαισίου. |
| [getCenterY()](#getCenterY--) | Επιστρέφει τη συντεταγμένη Y του κέντρου ενός πλαισίου. |
| [getFlipH()](#getFlipH--) | Καθορίζει αν ένα πλαίσιο είναι αναστροφή οριζόντια. |
| [getFlipV()](#getFlipV--) | Καθορίζει αν ένα πλαίσιο είναι αναστροφή κάθετα. |
| [getRectangle()](#getRectangle--) | Επιστρέφει τις συντεταγμένες ενός πλαισίου. |
| [deepClone()](#deepClone--) | Δημιουργεί αντίγραφο |
| [cloneT()](#cloneT--) | Δημιουργεί αντίγραφο. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα καθορισμένο αντικείμενο. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα καθορισμένο αντικείμενο. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Δημιουργεί νέες ιδιότητες πλαισίου σχήματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X ενός πλαισίου. |
| y | float | Συντεταγμένη Y ενός πλαισίου. |
| width | float | Πλάτος ενός πλαισίου. |
| height | float | Ύψος ενός πλαισίου. |
| flipH | byte | True εάν ένα πλαίσιο είναι αναστροφή οριζόντια. |
| flipV | byte | True εάν ένα πλαίσιο είναι αναστροφή κάθετα. |
| rotationAngle | float | Αριθμός μοιρών που το πλαίσιο είναι περιστραμμένο. |
### getX() {#getX--}
```
public final float getX()
```

Επιστρέφει τη συντεταγμένη X της επάνω-αριστερής γωνίας ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getY() {#getY--}
```
public final float getY()
```

Επιστρέφει τη συντεταγμένη Y της επάνω-αριστερής γωνίας ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Επιστρέφει το πλάτος ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Επιστρέφει το ύψος ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Επιστρέφει τον αριθμό μοιρών κατά τις οποίες ένα πλαίσιο περιστρέφεται γύρω από τον άξονα z. Θετική τιμή δείχνει δεξιόστροφη περιστροφή· αρνητική τιμή δείχνει αριστερόστροφη περιστροφή. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Επιστρέφει τη συντεταγμένη X του κέντρου ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Επιστρέφει τη συντεταγμένη Y του κέντρου ενός πλαισίου. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Καθορίζει αν ένα πλαίσιο είναι αναστροφή οριζόντια. Μόνο για ανάγνωση [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Καθορίζει αν ένα πλαίσιο είναι αναστροφή κάθετα. Μόνο για ανάγνωση [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Επιστρέφει τις συντεταγμένες ενός πλαισίου. Μόνο για ανάγνωση java.awt.geom.Rectangle2D.Float.

**Επιστρέφει:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Δημιουργεί αντίγραφο

**Επιστρέφει:**
java.lang.Object - Αντιγραμμένο πλαίσιο σχήματος.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Δημιουργεί αντίγραφο.

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Αντιγραμμένο πλαίσιο σχήματος.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Επιστρέφει:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα καθορισμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο προς σύγκριση με αυτήν την παρουσία. |

**Επιστρέφει:**
boolean - **true** εάν obj είναι ένα ShapeFrame που έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα καθορισμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Το ShapeFRameEx προς σύγκριση με αυτήν την παρουσία. |

**Επιστρέφει:**
boolean - **true** εάν value είναι ένα ShapeFrame που έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά, **false**.