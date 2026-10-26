---
title: GroupShape
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει μια ομάδα σχημάτων σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/groupshape/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

Αντιπροσωπεύει μια ομάδα σχημάτων σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. |
| [getGroupShapeLock()](#getGroupShapeLock--) | Επιστρέφει τις κλειδώσεις του σχήματος. |
| [getShapes()](#getShapes--) | Επιστρέφει τη συλλογή των σχημάτων μέσα στην ομάδα. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: Επιστρέφει null για αντικείμενα GroupShape επειδή δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [ILineFormat](../../com.aspose.slides/ilineformat).

**Επιστρέφει:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**Επιστρέφει:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Επιστρέφει τη συλλογή των σχημάτων μέσα στην ομάδα. Μόνο για ανάγνωση [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Επιστρέφει:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)