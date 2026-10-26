---
title: GeometryShape
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά την υπερκλάση για όλα τα γεωμετρικά σχήματα.
type: docs
url: /el/com.aspose.slides/geometryshape/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public abstract class GeometryShape extends Shape implements IGeometryShape
```

Αναπαριστά την υπερκλάση για όλα τα γεωμετρικά σχήματα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getGeometryPaths()](#getGeometryPaths--) | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. |
| [setGeometryPath(IGeometryPath geometryPath)](#setGeometryPath-com.aspose.slides.IGeometryPath-) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [setGeometryPaths(IGeometryPath[] geometryPaths)](#setGeometryPaths-com.aspose.slides.IGeometryPath---) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα των [IGeometryPath](../../com.aspose.slides/igeometrypath). |
| [getShapeStyle()](#getShapeStyle--) | Επιστρέφει το αντικείμενο στυλ του σχήματος. |
| [getShapeType()](#getShapeType--) | Επιστρέφει ή ορίζει τον προκαθορισμένο τύπο γεωμετρίας. |
| [setShapeType(int value)](#setShapeType-int-) | Επιστρέφει ή ορίζει τον προκαθορισμένο τύπο γεωμετρίας. |
| [getAdjustments()](#getAdjustments--) | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος. |
| [createShapeElements()](#createShapeElements--) | Δημιουργεί και επιστρέφει πίνακα των στοιχείων του σχήματος. |
### getGeometryPaths() {#getGeometryPaths--}
```
public final IGeometryPath[] getGeometryPaths()
```

Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του σχήματος.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
com.aspose.slides.IGeometryPath[] - Πίνακας των [IGeometryPath](../../com.aspose.slides/igeometrypath)
### setGeometryPath(IGeometryPath geometryPath) {#setGeometryPath-com.aspose.slides.IGeometryPath-}
```
public final void setGeometryPath(IGeometryPath geometryPath)
```

Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [IGeometryPath](../../com.aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) σε [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape) pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      GeometryPath geometryPath0 = new GeometryPath();
>      geometryPath0.moveTo(0, 0);
>      geometryPath0.lineTo(shape.getWidth(), 0);
>      geometryPath0.lineTo(shape.getWidth(), shape.getHeight()/3);
>      geometryPath0.lineTo(0, shape.getHeight() / 3);
>      geometryPath0.closeFigure();
>      GeometryPath geometryPath1 = new GeometryPath();
>      geometryPath1.moveTo(0, shape.getHeight()/3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight() / 3 * 2);
>      geometryPath1.lineTo(shape.getWidth(), shape.getHeight());
>      geometryPath1.lineTo(0, shape.getHeight());
>      geometryPath1.closeFigure();
>      shape.setGeometryPaths(new GeometryPath[] { geometryPath0, geometryPath1});
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryPath | [IGeometryPath](../../com.aspose.slides/igeometrypath) | Διαδρομή γεωμετρίας |

### setGeometryPaths(IGeometryPath[] geometryPaths) {#setGeometryPaths-com.aspose.slides.IGeometryPath---}
```
public final void setGeometryPaths(IGeometryPath[] geometryPaths)
```

Ενημερώνει τη γεωμετρία του σχήματος από πίνακα των [IGeometryPath](../../com.aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος (ShapeType(\#getShapeType.getShapeType/\#setShapeType(int).setShapeType(int))) σε [ShapeType.Custom](../../com.aspose.slides/shapetype\#Custom).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      GeometryShape shape = (GeometryShape)pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 200, 100);
>      IGeometryPath geometryPath = shape.getGeometryPaths()[0];
>      geometryPath.lineTo(100, 50, 1);
>      geometryPath.lineTo(100, 50, 4);
>      shape.setGeometryPath(geometryPath);
>      pres.save("output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| geometryPaths | [IGeometryPath\[\]](../../com.aspose.slides/igeometrypath) | Πίνακας διαδρομών γεωμετρίας |

### getShapeStyle() {#getShapeStyle--}
```
public final IShapeStyle getShapeStyle()
```

Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο για ανάγνωση [IShapeStyle](../../com.aspose.slides/ishapestyle).

**Επιστρέφει:**
[IShapeStyle](../../com.aspose.slides/ishapestyle)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Επιστρέφει ή ορίζει τον προκαθορισμένο τύπο γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής, όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλεγμένες τιμές. Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Επιστρέφει:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Επιστρέφει ή ορίζει τον προκαθορισμένο τύπο γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής, όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλεγμένες τιμές. Ανάγνωση/εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAdjustments() {#getAdjustments--}
```
public final IAdjustValueCollection getAdjustments()
```

Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος. Μόνο για ανάγνωση [IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection).

**Επιστρέφει:**
[IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
### createShapeElements() {#createShapeElements--}
```
public final IShapeElement[] createShapeElements()
```

Δημιουργεί και επιστρέφει πίνακα των στοιχείων του σχήματος.

**Επιστρέφει:**
com.aspose.slides.IShapeElement[] - Πίνακας των [ShapeElement](../../com.aspose.slides/shapeelement)