---
title: GeometryPath
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει τη γεωμετρική διαδρομή του GeometryShape
type: docs
url: /el/com.aspose.slides/geometrypath/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Αναπαριστά τη γεωμετρική διαδρομή του GeometryShape
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Δημιουργεί μια παρουσία του GeometryPath |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPathData()](#getPathData--) | Επιστρέφει τη γεωμετρική διαδρομή του GeometryShape ως πίνακα τμημάτων διαδρομής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το τμήμα στην καθορισμένη θέση της γεωμετρικής διαδρομής. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Προσθέτει γραμμή στο τέλος της διαδρομής. |
| [lineTo(float x, float y)](#lineTo-float-float-) | Προσθέτει γραμμή στο τέλος της διαδρομής. |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής. |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Προσθέτει κυρτή καμπύλη Bezier στο τέλος της διαδρομής. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Προσθέτει κυρτή καμπύλη Bezier στο τέλος της διαδρομής. |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Προσθέτει κυρτή καμπύλη Bezier στην καθορισμένη θέση της διαδρομής. |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Προσθέτει κυρτή καμπύλη Bezier στην καθορισμένη θέση της διαδρομής. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής. |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής. |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής. |
| [closeFigure()](#closeFigure--) | Κλείνει το τρέχον σχήμα αυτής της διαδρομής. |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Ορίζει τη θέση του επόμενου σημείου. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ορίζει τη θέση του επόμενου σημείου. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Προσθέτει το καθορισμένο τόξο στη διαδρομή. |
| [getFillMode()](#getFillMode--) | Ορίζει τη λειτουργία γεμίσματος. |
| [setFillMode(byte value)](#setFillMode-byte-) | Ορίζει τη λειτουργία γεμίσματος. |
| [getStroke()](#getStroke--) | Ορίζει την εμφάνιση της γραμμής. |
| [setStroke(boolean value)](#setStroke-boolean-) | Ορίζει την εμφάνιση της γραμμής. |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Δημιουργεί μια παρουσία του GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Επιστρέφει τη γεωμετρική διαδρομή του GeometryShape ως πίνακα τμημάτων διαδρομής.

**Επιστρέφει:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το τμήμα στην καθορισμένη θέση της γεωμετρικής διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της γεωμετρικής διαδρομής που πρέπει να διαγραφεί. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Προσθέτει γραμμή στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Τελικό σημείο της γραμμής |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Προσθέτει γραμμή στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του τελικού σημείου της γραμμής |
| y | float | Συντεταγμένη Y του τελικού σημείου της γραμμής |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Προσθέτει γραμμή στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του σημείου |
| y | float | Συντεταγμένη Y του σημείου |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Προσθέτει κυρτή καμπύλη Bezier στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Πρώτο σημείο κατεύθυνσης |
| point2 | java.awt.geom.Point2D.Float | Δεύτερο σημείο κατεύθυνσης |
| point3 | java.awt.geom.Point2D.Float | Τελικό σημείο |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Προσθέτει κυρτή καμπύλη Bezier στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του πρώτου σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του πρώτου σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του δεύτερου σημείου κατεύθυνσης |
| y2 | float | Συντεταγμένη Y του δεύτερου σημείου κατεύθυνσης |
| x3 | float | Συντεταγμένη X του τελικού σημείου |
| y3 | float | Συντεταγμένη Y του τελικού σημείου |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Προσθέτει κυρτή καμπύλη Bezier στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Πρώτο σημείο κατεύθυνσης |
| point2 | java.awt.geom.Point2D.Float | Δεύτερο σημείο κατεύθυνσης |
| point3 | java.awt.geom.Point2D.Float | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Προσθέτει κυρτή καμπύλη Bezier στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του πρώτου σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του πρώτου σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του δεύτερου σημείου κατεύθυνσης |
| y2 | float | Συντεταγμένη Y του δεύτερου σημείου κατεύθυνσης |
| x3 | float | Συντεταγμένη X του τελικού σημείου |
| y3 | float | Συντεταγμένη Y του τελικού σημείου |
| index | long | Δείκτης του τμήματος στο PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Σημείο κατεύθυνσης |
| point2 | java.awt.geom.Point2D.Float | Τελικό σημείο |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του τελικού σημείου |
| y2 | float | Συντεταγμένη Y του τελικού σημείου |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Σημείο κατεύθυνσης |
| point2 | java.awt.geom.Point2D.Float | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Προσθέτει τετραγωνική καμπύλη Bezier στην καθορισμένη θέση της διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του τελικού σημείου |
| y2 | float | Συντεταγμένη Y του τελικού σημείου |
| index | long | Δείκτης του τμήματος στο PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Κλείνει το τρέχον σχήμα αυτής της διαδρομής.

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Ορίζει τη θέση του επόμενου σημείου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Θέση σημείου |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Ορίζει τη θέση του επόμενου σημείου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του σημείου |
| y | float | Συντεταγμένη Y του σημείου |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Προσθέτει το καθορισμένο τόξο στη διαδρομή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Πλάτος του ορθογωνίου |
| heigth | float | Ύψος του ορθογωνίου |
| startAngle | float | Αρχική γωνία. |
| sweepAngle | float | Γωνία σάρωσης/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Ορίζει τη λειτουργία γεμίσματος.

**Επιστρέφει:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Ορίζει τη λειτουργία γεμίσματος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Ορίζει την εμφάνιση της γραμμής.

**Επιστρέφει:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Ορίζει την εμφάνιση της γραμμής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |