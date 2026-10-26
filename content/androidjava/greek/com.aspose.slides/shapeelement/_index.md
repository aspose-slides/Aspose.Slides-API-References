---
title: ShapeElement
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα μέρος του σχήματος με ίδιες ιδιότητες περιγράμματος και γεμίσματος.
type: docs
url: /el/com.aspose.slides/shapeelement/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Αντιπροσωπεύει ένα μέρος του σχήματος με τις ίδιες ιδιότητες περιγράμματος και γεμίσματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParentShape()](#getParentShape--) | Επιστρέφει ένα Shape_PPT για το οποίο δημιουργήθηκε το στοιχείο. |
| [getPathPoints()](#getPathPoints--) | Λαμβάνει έναν πίνακα σημείων που ορίζουν τη γεωμετρία του μονοπατιού του στοιχείου. |
| [getPathTypes()](#getPathTypes--) | Λαμβάνει έναν πίνακα τιμών byte που καθορίζουν τον τύπο κάθε σημείου στο μονοπάτι του στοιχείου. |
| [getFillSource()](#getFillSource--) | Επιστρέφει πληροφορίες σχετικά με το πώς να γεμίσει ένα στοιχείο. |
| [getStrokeSource()](#getStrokeSource--) | Επιστρέφει πληροφορίες σχετικά με το πώς να σχεδιάσει το περίγραμμα ενός στοιχείου. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Επιστρέφει ένα Shape_PPT για το οποίο δημιουργήθηκε το στοιχείο. Μόνο για ανάγνωση [Shape](../../com.aspose.slides/shape).

**Επιστρέφει:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Λαμβάνει έναν πίνακα σημείων που ορίζουν τη γεωμετρία του μονοπατιού του στοιχείου.

**Επιστρέφει:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Λαμβάνει έναν πίνακα τιμών byte που καθορίζουν τον τύπο κάθε σημείου στο μονοπάτι του στοιχείου.

**0** Δείχνει ότι το σημείο είναι η αρχή ενός σχήματος.

**1** Δείχνει ότι το σημείο είναι ένα από τα δύο άκρα μιας γραμμής.

**3** Δείχνει ότι το σημείο είναι άκρο ή σημείο ελέγχου μιας κυβικής καμπύλης Bezier.

**7** Καλύπτει όλα τα bits εκτός από τα τρία χαμηλότερα bits, που υποδεικνύουν τον τύπο του σημείου.

**16** Καθορίζει ότι το αντίστοιχο τμήμα είναι με διακεκομμένες γραμμές.

**32** Καθορίζει ότι το σημείο είναι δείκτης.

**128** Καθορίζει ότι το σημείο είναι το τελευταίο σημείο σε ένα κλειστό υπο-μονοπάτι (σχήμα).

**129** Δείχνει ένα σημείο δεδομένων που είναι ταυτόχρονα άκρο τμήματος γραμμής και το τελευταίο σημείο ενός κλειστού υπο-μονοπατιού.

**Επιστρέφει:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Επιστρέφει πληροφορίες σχετικά με το πώς να γεμίσει ένα στοιχείο. Μόνο για ανάγνωση [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Επιστρέφει:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Επιστρέφει πληροφορίες σχετικά με το πώς να σχεδιάσει το περίγραμμα ενός στοιχείου. Μόνο για ανάγνωση [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Επιστρέφει:**
byte