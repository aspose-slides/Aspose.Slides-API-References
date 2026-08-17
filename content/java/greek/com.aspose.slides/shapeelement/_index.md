---
title: ShapeElement
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά ένα μέρος του σχήματος με ίδιες ιδιότητες περιγράμματος και γεμίσματος.
type: docs
url: /el/com.aspose.slides/shapeelement/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Αναπαριστά ένα μέρος του σχήματος με ίδιες ιδιότητες περιγράμματος και γεμίσματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParentShape()](#getParentShape--) | Επιστρέφει ένα Shape_PPT για το οποίο δημιουργήθηκε το στοιχείο. |
| [getPathPoints()](#getPathPoints--) | Λαμβάνει έναν πίνακα σημείων που ορίζουν τη γεωμετρία της διαδρομής του στοιχείου. |
| [getPathTypes()](#getPathTypes--) | Λαμβάνει έναν πίνακα τιμών byte που καθορίζουν τον τύπο κάθε σημείου στη διαδρομή του στοιχείου. |
| [getFillSource()](#getFillSource--) | Επιστρέφει πληροφορίες σχετικά με το πώς γεμίζει ένα στοιχείο. |
| [getStrokeSource()](#getStrokeSource--) | Επιστρέφει πληροφορίες σχετικά με το πώς σχεδιάζεται ένα στοιχείο. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Επιστρέφει ένα Shape_PPT για το οποίο δημιουργήθηκε το στοιχείο. Μόνο για ανάγνωση [Shape](../../com.aspose.slides/shape).

**Επιστρέφει:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Λαμβάνει έναν πίνακα σημείων που ορίζουν τη γεωμετρία της διαδρομής του στοιχείου.

**Επιστρέφει:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Λαμβάνει έναν πίνακα τιμών byte που καθορίζουν τον τύπο κάθε σημείου στη διαδρομή του στοιχείου.

**0** Υποδηλώνει ότι το σημείο είναι η αρχή ενός σχήματος.

**1** Υποδηλώνει ότι το σημείο είναι ένα από τα δύο άκρα μιας γραμμής.

**3** Υποδηλώνει ότι το σημείο είναι άκρο ή σημείο ελέγχου μιας κυβικής καμπύλης Bezier.

**7** Καλύπτει όλα τα bits εκτός από τα τρία χαμηλότερα bits, που υποδεικνύουν τον τύπο του σημείου.

**16** Καθορίζει ότι το αντίστοιχο τμήμα είναι διακεκομμένο.

**32** Καθορίζει ότι το σημείο είναι ένδειξη.

**128** Καθορίζει ότι το σημείο είναι το τελευταίο σημείο σε μια κλειστή υποδιαδρομή (σχήμα).

**129** Υποδηλώνει ένα σημείο δεδομένων που είναι και άκρο ενός τμήματος γραμμής και το τελευταίο σημείο μιας κλειστής υποδιαδρομής.

**Επιστρέφει:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Επιστρέφει πληροφορίες σχετικά με το πώς γεμίζει ένα στοιχείο. Μόνο για ανάγνωση [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Επιστρέφει:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Επιστρέφει πληροφορίες σχετικά με το πώς σχεδιάζεται ένα στοιχείο. Μόνο για ανάγνωση [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Επιστρέφει:**
byte