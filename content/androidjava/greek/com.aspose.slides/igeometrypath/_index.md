---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /el/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Αντιπροσωπεύει το γεωμετρικό μονοπάτι του GeometryShape
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPathData()](#getPathData--) | Επιστρέφει το γεωμετρικό μονοπάτι του GeometryShape ως έναν πίνακα τμημάτων μονοπατιού. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το τμήμα στο καθορισμένο δείκτη του γεωμετρικού μονοπατιού. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Προσθέτει γραμμή στο τέλος του μονοπατιού |
| [lineTo(float x, float y)](#lineTo-float-float-) | Προσθέτει γραμμή στο τέλος του μονοπατιού |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Προσθέτει κυρτή καμπύλη Bezier (cubic) στο τέλος του μονοπατιού |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Προσθέτει κυρτή καμπύλη Bezier (cubic) στο τέλος του μονοπατιού |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Προσθέτει κυρτή καμπύλη Bezier (cubic) στη συγκεκριμένη θέση του μονοπατιού |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Προσθέτει κυρτή καμπύλη Bezier (cubic) στη συγκεκριμένη θέση του μονοπατιού |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στο τέλος του μονοπατιού |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στο τέλος του μονοπατιού |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στη συγκεκριμένη θέση του μονοπατιού |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στη συγκεκριμένη θέση του μονοπατιού |
| [closeFigure()](#closeFigure--) | Κλείνει το τρέχον σχήμα αυτού του μονοπατιού |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Ορίζει τη θέση του επόμενου σημείου. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ορίζει τη θέση του επόμενου σημείου. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Προσαρτά το καθορισμένο τόξο στο μονοπάτι. |
| [getFillMode()](#getFillMode--) | Ορίζει τη λειτουργία γεμίσματος |
| [setFillMode(byte value)](#setFillMode-byte-) | Ορίζει τη λειτουργία γεμίσματος |
| [getStroke()](#getStroke--) | Ορίζει την εμφάνιση της γραμμής περιγράμματος |
| [setStroke(boolean value)](#setStroke-boolean-) | Ορίζει την εμφάνιση της γραμμής περιγράμματος |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Επιστρέφει το γεωμετρικό μονοπάτι του GeometryShape ως έναν πίνακα τμημάτων μονοπατιού.

**Επιστρέφει:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Αφαιρεί το τμήμα στο καθορισμένο δείκτη του γεωμετρικού μονοπατιού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του γεωμετρικού μονοπατιού που πρέπει να διαγραφεί. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


Προσθέτει γραμμή στο τέλος του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Τελικό σημείο της γραμμής |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Προσθέτει γραμμή στο τέλος του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του τελικού σημείου της γραμμής |
| y | float | Συντεταγμένη Y του τελικού σημείου της γραμμής |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Προσθέτει γραμμή στη συγκεκριμένη θέση του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του σημείου |
| y | float | Συντεταγμένη Y του σημείου |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Προσθέτει κυρτή καμπύλη Bezier (cubic) στο τέλος του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Πρώτο σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Δεύτερο σημείο κατεύθυνσης |
| point3 | android.graphics.PointF | Τελικό σημείο |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Προσθέτει κυρτή καμπύλη Bezier (cubic) στο τέλος του μονοπατιού

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
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Προσθέτει κυρτή καμπύλη Bezier (cubic) στη συγκεκριμένη θέση του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Πρώτο σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Δεύτερο σημείο κατεύθυνσης |
| point3 | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Προσθέτει κυρτή καμπύλη Bezier (cubic) στη συγκεκριμένη θέση του μονοπατιού

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
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στο τέλος του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Τελικό σημείο |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στο τέλος του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x1 | float | Συντεταγμένη X του σημείου κατεύθυνσης |
| y1 | float | Συντεταγμένη Y του σημείου κατεύθυνσης |
| x2 | float | Συντεταγμένη X του τελικού σημείου |
| y2 | float | Συντεταγμένη Y του τελικού σημείου |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στη συγκεκριμένη θέση του μονοπατιού

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | android.graphics.PointF | Σημείο κατεύθυνσης |
| point2 | android.graphics.PointF | Τελικό σημείο |
| index | long | Δείκτης του τμήματος στο PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Προσθέτει τετραγωνική καμπύλη Bezier (quadratic) στη συγκεκριμένη θέση του μονοπατιού

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
public abstract void closeFigure()
```


Κλείνει το τρέχον σχήμα αυτού του μονοπατιού

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


Ορίζει τη θέση του επόμενου σημείου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | android.graphics.PointF | Θέση του σημείου |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Ορίζει τη θέση του επόμενου σημείου.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Συντεταγμένη X του σημείου |
| y | float | Συντεταγμένη Y του σημείου |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Προσαρτά το καθορισμένο τόξο στο μονοπάτι.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Πλάτος του ορθογωνίου |
| heigth | float | Ύψος του ορθογωνίου |
| startAngle | float | Γωνία έναρξης. |
| sweepAngle | float | Γωνία σάρωσης/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Ορίζει τη λειτουργία γεμίσματος

**Επιστρέφει:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Ορίζει τη λειτουργία γεμίσματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Ορίζει την εμφάνιση της γραμμής περιγράμματος

**Επιστρέφει:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Ορίζει την εμφάνιση της γραμμής περιγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |