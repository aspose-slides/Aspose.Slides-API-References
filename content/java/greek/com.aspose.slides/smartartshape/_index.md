---
title: SmartArtShape
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά σχήμα SmartArt
type: docs
url: /el/com.aspose.slides/smartartshape/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Αναπαριστά το σχήμα SmartArt
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShapeType()](#getShapeType--) | Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. |
| [setShapeType(int value)](#setShapeType-int-) | Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. |
| [getTextFrame()](#getTextFrame--) | Επιστρέφει το κείμενο του σχήματος SmartArt. |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επαναφερθούν στις προεπιλεγμένες τιμές. Ανάγνωση/Εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Επιστρέφει:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επαναφερθούν στις προεπιλεγμένες τιμές. Ανάγνωση/Εγγραφή [ShapeType](../../com.aspose.slides/shapetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Επιστρέφει το κείμενο του σχήματος SmartArt. Μόνο για ανάγνωση [ITextFrame](../../com.aspose.slides/itextframe).

**Επιστρέφει:**
[ITextFrame](../../com.aspose.slides/itextframe)