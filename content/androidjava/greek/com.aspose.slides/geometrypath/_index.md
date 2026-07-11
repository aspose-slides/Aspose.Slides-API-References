---
title: GeometryPath
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη γεωμετρική διαδρομή του GeometryShape
type: docs
url: /el/com.aspose.slides/geometrypath/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Αναπαριστά τη γεωμετρική διαδρομή του GeometryShape
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Creates instance of GeometryPath |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPathData()](#getPathData--) | Returns geometry path of GeometryShape as an array of path segments. |
| [removeAt(int index)](#removeAt-int-) | Removes segment at the specified index of the geometry path. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Adds line to the end of the path |
| [lineTo(float x, float y)](#lineTo-float-float-) | Adds line to the end of the path |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Adds line to the specified place of the path |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Adds line to the specified place of the path |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Adds cubic Bezier curve to the specified place of the path |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Adds cubic Bezier curve to the specified place of the path |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Adds quadratic Bezier curve to the specified place of the path |
| [closeFigure()](#closeFigure--) | Closes the current figure of this path |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Sets next point position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Sets next point position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Appends the specified arc to the path. |
| [getFillMode()](#getFillMode--) | Sets fill mode |
| [setFillMode(byte value)](#setFillMode-byte-) | Sets fill mode |
| [getStroke()](#getStroke--) | Sets stroke appearance |
| [setStroke(boolean value)](#setStroke-boolean-) | Sets stroke appearance |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Δημιουργεί ένα στιγμιότυπο του GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Επιστρέφει τη γεωμετρική διαδρομή του GeometryShape ως έναν πίνακα τμημάτων διαδρομής.

**Επιστρέφει:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το τμήμα στο καθορισμένο δείκτη της γεωμετρικής διαδρομής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της γεωμετρικής διαδρομής που πρέπει να διαγραφεί. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Προσθέτει γραμμή στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Τελικό σημείο της γραμμής |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Προσθέτει γραμμή στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του τελικού σημείου της γραμμής |
| y | float | Συντεταγμένη Y του τελικού σημείου της γραμμής |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Προσθέτει γραμμή στο καθορισμένο σημείο της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Προσθέτει γραμμή στο καθορισμένο σημείο της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του σημείου |
| y | float | Συντεταγμένη Y του σημείου |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Πρώτο σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Δεύτερο σημείο κατεύθυνσης |
| point3 | android.graphics.PointF | Τελικό σημείο |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Προσθέτει κυβική καμπύλη Bezier στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του πρώτου σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του πρώτου σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του δεύτερου σημείου κατεύθυνσης |
| y2 | float | Συντεταγμένη Y του δεύτερου σημείου κατεύθυνσης |
| x3 | float | Συντεταγμένη X του τελικού σημείου |
| y3 | float | Συντεταγμένη Y του τελικού σημείου |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Προσθέτει κυβική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Πρώτο σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Δεύτερο σημείο κατεύθυνσης |
| point3 | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Προσθέτει κυβική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής

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

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Τελικό σημείο |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο τέλος της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του τελικού σημείου |
| y2 | float | Συντεταγμένη Y του τελικού σημείου |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Προσθέτει τετραγωνική καμπύλη Bezier στο καθορισμένο σημείο της διαδρομής

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

Κλείνει το τρέχον σχήμα αυτής της διαδρομής

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Ορίζει τη θέση του επόμενου σημείου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Θέση σημείου |

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

Προσθέτει την καθορισμένη τόξο στη διαδρομή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Πλάτος του ορθογωνίου |
| heigth | float | Ύψος του ορθογωνίου |
| startAngle | float | Αρχική γωνία. |
| sweepAngle | float | Γωνία σάρωσης. |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Ορίζει τη λειτουργία γεμίσματος

**Επιστρέφει:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Ορίζει τη λειτουργία γεμίσματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Ορίζει την εμφάνιση του περιγράμματος

**Επιστρέφει:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Ορίζει την εμφάνιση του περιγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |