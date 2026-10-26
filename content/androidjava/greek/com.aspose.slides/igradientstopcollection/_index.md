---
title: IGradientStopCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή σημείων διαβάθμισης.
type: docs
url: /el/com.aspose.slides/igradientstopcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Αναπαριστά μια συλλογή από διαβαθμιστικά σημεία.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο διαβάθμισης με βάση το δείκτη. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί ένα σημείο διαβάθμισης στη συγκεκριμένη θέση. |
| [clear()](#clear--) | Καταργεί όλα τα σημεία διαβάθμισης από μια συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Επιστρέφει το σημείο διαβάθμισης με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| color | java.lang.Integer | Το χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Το χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το προσθέτει στο τέλος της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Το χρώμα του νέου σημείου διαβάθμισης. |

**Επιστρέφει:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Δείκτης του νέου σημείου διαβάθμισης στη συλλογή.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| color | java.lang.Integer | Το χρώμα του νέου σημείου διαβάθμισης. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| presetColor | int | Το χρώμα του νέου σημείου διαβάθμισης. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Δημιουργεί το νέο σημείο διαβάθμισης και το εισάγει στη συλλογή στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης στη συλλογή όπου θα εισαχθεί το νέο σημείο διαβάθμισης. |
| position | float | Η θέση του νέου σημείου διαβάθμισης. |
| schemeColor | int | Το χρώμα του νέου σημείου διαβάθμισης. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Καταργεί ένα σημείο διαβάθμισης στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης ενός σημείου διαβάθμισης που θα διαγραφεί. |

### clear() {#clear--}
```
public abstract void clear()
```


Καταργεί όλα τα σημεία διαβάθμισης από μια συλλογή.