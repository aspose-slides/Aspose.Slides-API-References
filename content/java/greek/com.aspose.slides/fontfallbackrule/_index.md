---
title: FontFallBackRule
second_title: Aspose.Slides για Java - Αναφορά API
description: Αναπαριστά τον κανόνα εναλλακτικής γραμματοσειράς
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

Αναπαριστά τον κανόνα εναλλακτικής γραμματοσειράς
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Δημιουργεί νέα παρουσία. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Δημιουργεί νέα παρουσία. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Προσθέτει νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Λαμβάνει τον πρώτο δείκτη της συνεχούς περιοχής Unicode. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Λαμβάνει τον πρώτο δείκτη της συνεχούς περιοχής Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Λαμβάνει τον τελευταίο δείκτη της συνεχούς περιοχής Unicode. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Λαμβάνει τον τελευταίο δείκτη της συνεχούς περιοχής Unicode. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των γραμματοσειρών που ορίζονται πραγματικά για την περιοχή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το όνομα της γραμματοσειράς στο καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις γραμματοσειρές από τη λίστα. |
| [remove(String fontName)](#remove-java.lang.String-) | Αφαιρεί το πρώτο εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη γραμματοσειρά FallBack στον καθορισμένο δείκτη της λίστας. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από την καθορισμένη περιοχή στη λίστα. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Επιστρέφει το δείκτη του καθορισμένου κανόνα στη συλλογή. |
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
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικός δείκτης της περιοχής Unicode |
| endIndex | long | Τελικός δείκτης της περιοχής Unicode |
| fontNames | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

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
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | long | Αρχικός δείκτης της περιοχής Unicode |
| endIndex | long | Τελικός δείκτης της περιοχής Unicode |
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Προσθέτει νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack.

--------------------

> ```
> // Δημιουργήστε νέα παρουσία του FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθέστε δεύτερη γραμματοσειρά στον κανόνα 
>  newRule.addFallBackFonts("MS Gothic");
>  //Προσθέστε τρίτη και τέταρτη γραμματοσειρές στον κανόνα 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack.

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
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Λαμβάνει τον πρώτο δείκτη της συνεχούς περιοχής Unicode.

**Επιστρέφει:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Λαμβάνει τον πρώτο δείκτη της συνεχούς περιοχής Unicode.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Λαμβάνει τον τελευταίο δείκτη της συνεχούς περιοχής Unicode.

**Επιστρέφει:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Λαμβάνει τον τελευταίο δείκτη της συνεχούς περιοχής Unicode.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Λαμβάνει τον αριθμό των γραμματοσειρών που ορίζονται πραγματικά για την περιοχή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Λαμβάνει το όνομα της γραμματοσειράς στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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


Αφαιρεί όλες τις γραμματοσειρές από τη λίστα.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Αφαιρεί το πρώτο εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.

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
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα αφαιρεθεί από τη λίστα. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Αφαιρεί τη γραμματοσειρά FallBack στον καθορισμένο δείκτη της λίστας.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Αφαίρεση του Tahoma από τη λίστα.
>  newRule.remove(2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενική-βάση δείκτης της γραμματοσειράς που θα αφαιρεθεί. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Λάβετε όλα τα ονόματα γραμματοσειρών ως πίνακα.
>  String[] fontNames = newRule.toArray();
> ```

**Επιστρέφει:**
java.lang.String[] - Πίνακας String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από την καθορισμένη περιοχή στη λίστα.

```
// Δημιουργήστε έναν κανόνα που περιέχει λίστα γραμματοσειρών.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Λάβετε τα τελευταία δύο ονόματα γραμματοσειρών ως πίνακα.
 String[] fontNames = newRule.toArray(2, 2);
```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης γραμματοσειράς που θα προστεθεί. |
| count | int | Αριθμός γραμματοσειρών που θα προστεθούν. |

**Επιστρέφει:**
java.lang.String[] - Πίνακας String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Επιστρέφει το δείκτη του καθορισμένου κανόνα στη συλλογή.

--------------------

> ```
> // Δημιουργήστε έναν κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Λάβετε το δείκτη του Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα βρεθεί. |

**Επιστρέφει:**
int - Δείκτης μιας γραμματοσειράς ή -1 εάν η γραμματοσειρά δεν βρέθηκε στη λίστα.