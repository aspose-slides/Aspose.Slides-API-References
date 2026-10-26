---
title: Tab
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια εσοχή για κείμενο.
type: docs
url: /el/com.aspose.slides/tab/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Αντιπροσωπεύει μια εσοχή για κείμενο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Creates new Tab |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returns or sets position of a tab. |
| [setPosition(double value)](#setPosition-double-) | Returns or sets position of a tab. |
| [getAlignment()](#getAlignment--) | Returns or sets align style of a tab. |
| [setAlignment(int value)](#setAlignment-int-) | Returns or sets align style of a tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the current instance with another object of the same type. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Δημιουργεί νέο Tab

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | double | Tab position. |
| align | int | Align. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Επιστρέφει ή ορίζει τη θέση μιας εσοχής. Η ανάθεση αυτής της ιδιότητας μπορεί να αλλάξει τον δείκτη της εσοχής στη συλλογή και να ακυρώσει τον Enumerator. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Επιστρέφει ή ορίζει τη θέση μιας εσοχής. Η ανάθεση αυτής της ιδιότητας μπορεί να αλλάξει τον δείκτη της εσοχής στη συλλογή και να ακυρώσει τον Enumerator. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Επιστρέφει ή ορίζει το στυλ στοίχισης μιας εσοχής. Ανάγνωση/εγγραφή [TabAlignment](../../com.aspose.slides/tabalignment).

**Επιστρέφει:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Επιστρέφει ή ορίζει το στυλ στοίχισης μιας εσοχής. Ανάγνωση/εγγραφή [TabAlignment](../../com.aspose.slides/tabalignment).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Συγκρίνει την τρέχουσα περίπτωση με ένα άλλο αντικείμενο του ίδιου τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Ένα αντικείμενο για σύγκριση με αυτή την περίπτωση. |

**Επιστρέφει:**
int - Ένας ακέραιος 32-bit που υποδεικνύει τη σχετική σειρά των συγκριμένων. Η τιμή επιστροφής έχει τις εξής έννοιες: 

 * < 0 - Αυτό το αντικείμενο είναι μικρότερο από obj.
 * = 0 - Αυτό το αντικείμενο είναι ίσο με obj.
 * > 0 - Αυτό το αντικείμενο είναι μεγαλύτερο από obj.