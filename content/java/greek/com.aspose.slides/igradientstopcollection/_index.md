---
title: IGradientStopCollection
second_title: Aspose.Slides για την αναφορά API της Java
description: Αντιπροσωπεύει μια συλλογή από σημεία διαβάθμισης.
type: docs
url: /el/com.aspose.slides/igradientstopcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Αντιπροσωπεύει μια συλλογή από σημεία διαβάθμισης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο διαβάθμισης με το δείκτη. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί ένα σημείο διαβάθμισης στην καθορισμένη θέση. |
| [clear()](#clear--) | Αφαιρεί όλα τα σημεία διαβάθμισης από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Επιστρέφει το σημείο διαβάθμισης με το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| color | java.awt.Color | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Δημιουργεί νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| color | java.awt.Color | Χρώμα του νέου σημείου διαβάθμισης. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Χρώμα του νέου σημείου διαβάθμισης. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Δημιουργεί νέο σημείο διαβάθμισης και το εισάγει στην καθορισμένη θέση στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Χρώμα του νέου σημείου διαβάθμισης. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί ένα σημείο διαβάθμισης στην καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση του σημείου διαβάθμισης που πρέπει να διαγραφεί. |
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα σημεία διαβάθμισης από τη συλλογή.