---
title: FontFallBackRule
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά τον κανόνα υποκατάστασης γραμματοσειράς
type: docs
url: /el/com.aspose.slides/fontfallbackrule/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Αναπαριστά τον κανόνα υποκατάστασης γραμματοσειράς
## Constructors

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Δημιουργεί νέα παρουσία. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Δημιουργεί νέα παρουσία. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών υποκατάστασης. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών υποκατάστασης. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Λαμβάνει τον πρώτο δείκτη του συνεχόμενου εύρους Unicode. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Λαμβάνει τον πρώτο δείκτη του συνεχόμενου εύρους Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Λαμβάνει τον τελευταίο δείκτη του συνεχόμενου εύρους Unicode. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Λαμβάνει τον τελευταίο δείκτη του συνεχόμενου εύρους Unicode. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των γραμματοσειρών που έχουν οριστεί για το εύρος. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το όνομα της γραμματοσειράς στον καθορισμένο δείκτη. |
| [clear()](#clear--) | Καταργεί όλες τις γραμματοσειρές από τη λίστα. |
| [remove(String fontName)](#remove-java.lang.String-) | Καταργεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς υποκατάστασης από τη λίστα. |
| [removeAt(int index)](#removeAt-int-) | Καταργεί τη γραμματοσειρά υποκατάστασης στον καθορισμένο δείκτη της λίστας. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές υποκατάστασης για αυτόν τον κανόνα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές υποκατάστασης από το καθορισμένο εύρος στη λίστα. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Επιστρέφει έναν δείκτη του καθορισμένου κανόνα στη συλλογή. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Δημιουργεί νέα παρουσία.

--------------------

> ```
> // Δημιουργήστε νέα παρουσία του FantFallBackRule με μία γραμματοσειρά.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Δημιουργήστε νέα παρουσία του FantFallBackRule με πολλές γραμματοσειρές.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικός δείκτης του εύρους Unicode |
| endIndex | long | Τελικός δείκτης του εύρους Unicode |
| fontNames | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για την υποκατάσταση |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Δημιουργεί νέα παρουσία.

--------------------

> ```
> // Δημιουργήστε νέα παρουσία του FantFallBackRule με δύο γραμματοσειρές
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Δημιουργήστε νέα παρουσία του FantFallBackRule με πολλές γραμματοσειρές.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικός δείκτης του εύρους Unicode |
| endIndex | long | Τελικός δείκτης του εύρους Unicode |
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για την υποκατάσταση |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών υποκατάστασης.

--------------------

> ```
> // Δημιουργήστε νέα παρουσία του FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθέστε μία δεύτερη γραμματοσειρά στον κανόνα 
>  newRule.addFallBackFonts("MS Gothic");
>  //Προσθέστε τρίτη και τέταρτη γραμματοσειρές στον κανόνα 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για την υποκατάσταση |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών υποκατάστασης.

--------------------

> ```
> //Δημιουργήστε νέα παρουσία του FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθέστε άλλες τρεις γραμματοσειρές στον κανόνα 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για την υποκατάσταση |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Λαμβάνει τον πρώτο δείκτη του συνεχόμενου εύρους Unicode.

**Επιστρέφει:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Λαμβάνει τον πρώτο δείκτη του συνεχόμενου εύρους Unicode.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Λαμβάνει τον τελευταίο δείκτη του συνεχόμενου εύρους Unicode.

**Επιστρέφει:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Λαμβάνει τον τελευταίο δείκτη του συνεχόμενου εύρους Unicode.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Αποκτά τον αριθμό των γραμματοσειρών που έχουν οριστεί για το εύρος. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Αποκτά το όνομα της γραμματοσειράς στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Καταργεί όλα τα γραμματοσειρές από τη λίστα.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Καταργεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς υποκατάστασης από τη λίστα.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Αφαιρέστε το Tahoma από τη λίστα.
>  newRule.remove("Tahoma");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς προς κατάργηση από τη λίστα. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Καταργεί τη γραμματοσειρά υποκατάστασης στον καθορισμένο δείκτη της λίστας.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Αφαίρεση του Tahoma από τη λίστα.
>  newRule.remove(2);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης της γραμματοσειράς προς κατάργηση. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές υποκατάστασης για αυτόν τον κανόνα.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Λάβετε όλα τα ονόματα γραμματοσειρών ως πίνακα.
>  String[] fontNames = newRule.toArray();
> ```


**Επιστρέφει:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές υποκατάστασης από το καθορισμένο εύρος στη λίστα.

```
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Λάβετε τις δύο τελευταίες ονομασίες γραμματοσειρών ως πίνακα.
 String[] fontNames = newRule.toArray(2, 2);
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης γραμματοσειράς προς προσθήκη. |
| count | int | Αριθμός γραμματοσειρών προς προσθήκη. |

**Επιστρέφει:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Επιστρέφει έναν δείκτη του καθορισμένου κανόνα στη συλλογή.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Λάβετε το δείκτη του Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς προς αναζήτηση. |

**Επιστρέφει:**
int - Δείκτης της γραμματοσειράς ή -1 αν δεν βρεθεί στη λίστα.