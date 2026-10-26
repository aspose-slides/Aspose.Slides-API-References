---
title: IDrawingGuidesCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά μια συλλογή ρυθμιζόμενων οδηγών σχεδίασης.
type: docs
url: /el/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Represents a collection of the adjustable drawing guides.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the drawing guide by index. |
| [add(byte orientation, float position)](#add-byte-float-) | Adds the drawing guide at the end of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the drawing guide at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Επιστρέφει τον οδηγό σχεδίασης με το ευρετήριο. Μόνο για ανάγνωση [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Προσθέτει τον οδηγό σχεδίασης στο τέλος της συλλογής.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | Προσανατολισμός του οδηγού σχεδίασης. |
| position | float | Θέση του οδηγού σχεδίασης σε μονάδες. |

**Returns:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τον οδηγό σχεδίασης στο καθορισμένο ευρετήριο.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης του οδηγού σχεδίασης που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Επιστρέφει τον αριθμό όλων των στοιχείων στη συλλογή. Μόνο για ανάγνωση int.

**Returns:**
int