---
title: ShapeFrame
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά τις ιδιότητες των πλαισίων σχήματος.
type: docs
url: /el/com.aspose.slides/shapeframe/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Αντιπροσωπεύει τις ιδιότητες του shape frame.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Δημιουργεί νέες ιδιότητες του shape frame. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getX()](#getX--) | Επιστρέφει τη συντεταγμένη X της επάνω-αριστερής γωνίας ενός frame. |
| [getY()](#getY--) | Επιστρέφει τη συντεταγμένη Y της επάνω-αριστερής γωνίας ενός frame. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος ενός frame. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος ενός frame. |
| [getRotation()](#getRotation--) | Επιστρέφει τον αριθμό των μοιρών κατά τις οποίες το frame περιστρέφεται γύρω από τον άξονα z. |
| [getCenterX()](#getCenterX--) | Επιστρέφει τη συντεταγμένη X του κέντρου ενός frame. |
| [getCenterY()](#getCenterY--) | Επιστρέφει τη συντεταγμένη Y του κέντρου ενός frame. |
| [getFlipH()](#getFlipH--) | Καθορίζει αν ένα frame έχει αντιστραφεί οριζόντια. |
| [getFlipV()](#getFlipV--) | Καθορίζει αν ένα frame έχει αντιστραφεί κάθετα. |
| [getRectangle()](#getRectangle--) | Επιστρέφει τις συντεταγμένες ενός frame. |
| [deepClone()](#deepClone--) | Κλωνοποιεί |
| [cloneT()](#cloneT--) | Κλωνοποιεί. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα συγκεκριμένο αντικείμενο. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα συγκεκριμένο αντικείμενο. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Δημιουργεί νέες ιδιότητες του shape frame.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | X coordinate of a frame. |
| y | float | Y coordinate of a frame. |
| width | float | Width of a frame. |
| height | float | Height of a frame. |
| flipH | byte | True if a frame flipped horizontally. |
| flipV | byte | True if a frame flipped vertivally. |
| rotationAngle | float | Number of degrees a frame is rotated. |

### getX() {#getX--}
```
public final float getX()
```


Επιστρέφει τη συντεταγμένη X της επάνω-αριστερής γωνίας ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getY() {#getY--}
```
public final float getY()
```


Επιστρέφει τη συντεταγμένη Y της επάνω-αριστερής γωνίας ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Επιστρέφει το πλάτος ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Επιστρέφει το ύψος ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Επιστρέφει τον αριθμό των μοιρών κατά τις οποίες το frame περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Επιστρέφει τη συντεταγμένη X του κέντρου ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Επιστρέφει τη συντεταγμένη Y του κέντρου ενός frame. Μόνο ανάγνωση float.

**Επιστρέφει:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Καθορίζει αν ένα frame είναι αντιστραμμένο οριζόντια. Μόνο ανάγνωση [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Καθορίζει αν ένα frame είναι αντιστραμμένο κάθετα. Μόνο ανάγνωση [NullableBool](../../com.aspose.slides/nullablebool).

**Επιστρέφει:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Επιστρέφει τις συντεταγμένες ενός frame. Μόνο ανάγνωση android.graphics.RectF.

**Επιστρέφει:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποιεί

**Επιστρέφει:**
java.lang.Object - Κλωνοποιημένο shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Κλωνοποιεί.

**Επιστρέφει:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Κλωνοποιημένο shape frame.
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


Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα συγκεκριμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για σύγκριση με αυτήν την παρουσία. |

**Επιστρέφει:**
boolean - **true** εάν obj είναι ένα ShapeFrame που έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με ένα συγκεκριμένο αντικείμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Το ShapeFRameEx για σύγκριση με αυτήν την παρουσία. |

**Επιστρέφει:**
boolean - **true** εάν value είναι ένα ShapeFrame που έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά, **false**.