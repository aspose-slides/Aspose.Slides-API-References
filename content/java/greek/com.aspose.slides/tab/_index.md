---
title: Tab
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά μια εσοχή κειμένου.
type: docs
url: /el/com.aspose.slides/tab/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Αναπαριστά μια εσοχή κειμένου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Δημιουργεί νέο Tab |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Επιστρέφει ή ορίζει τη θέση μιας εσοχής. |
| [setPosition(double value)](#setPosition-double-) | Επιστρέφει ή ορίζει τη θέση μιας εσοχής. |
| [getAlignment()](#getAlignment--) | Επιστρέφει ή ορίζει το στυλ στοίχισης μιας εσοχής. |
| [setAlignment(int value)](#setAlignment-int-) | Επιστρέφει ή ορίζει το στυλ στοίχισης μιας εσοχής. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Συγκρίνει την τρέχουσα παρουσία με άλλο αντικείμενο του ίδιου τύπου. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Δημιουργεί νέο Tab

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | double | Θέση Tab. |
| align | int | Στοίχιση. |

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


Επιστρέφει ή ορίζει τη θέση μιας εσοχής. Η ανάθεση αυτής της ιδιότητας μπορεί να αλλάξει το δείκτη της εσοχής στη συλλογή και να ακυρώσει τον Enumerator. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Επιστρέφει ή ορίζει τη θέση μιας εσοχής. Η ανάθεση αυτής της ιδιότητας μπορεί να αλλάξει το δείκτη της εσοχής στη συλλογή και να ακυρώσει τον Enumerator. Ανάγνωση/εγγραφή double.

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


Συγκρίνει την τρέχουσα παρουσία με άλλο αντικείμενο του ίδιου τύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Ένα αντικείμενο για σύγκριση με αυτήν την παρουσία. |

**Επιστρέφει:**
int - Ένας 32-bit ακέραιος που υποδεικνύει τη σχετική σειρά των συγκρινόμενων στοιχείων. Η τιμή επιστροφής έχει τις ακόλουθες σημασίες: 

 *  < 0 - Η παρουσία είναι μικρότερη από το obj.
 *  = 0 - Η παρουσία είναι ίση με το obj.
 *  > 0 - Η παρουσία είναι μεγαλύτερη από το obj.