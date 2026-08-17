---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά τον κανόνα εναλλακτικής γραμματοσειράς
type: docs
url: /el/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Αναπαριστά τον κανόνα εναλλακτικής γραμματοσειράς
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Λαμβάνει τον πρώτο δείκτη του συνεχούς εύρους Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Λαμβάνει τον τελευταίο δείκτη του συνεχούς εύρους Unicode. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των γραμματοσειρών που ορίζονται πραγματικά για το εύρος. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το όνομα της γραμματοσειράς στο καθορισμένο δείκτη. |
| [clear()](#clear--) | Αφαιρεί όλες τις γραμματοσειρές από τη λίστα. |
| [remove(String fontName)](#remove-java.lang.String-) | Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη γραμματοσειρά FallBack στο καθορισμένο δείκτη της λίστας. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από το καθορισμένο εύρος στη λίστα. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Επιστρέφει έναν δείκτη του καθορισμένου κανόνα στη συλλογή. |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Προσθέτει μια νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack.

--------------------

> ```
> //Δημιουργία νέας παρουσίας του FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθήκη δεύτερης γραμματοσειράς στον κανόνα 
>  newRule.addFallBackFonts("MS Gothic");
>  //Προσθήκη τρίτης και τέταρτης γραμματοσειρών στον κανόνα 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (χωρισμένα με κόμμα) για FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack.

--------------------

> ```
> //Δημιουργία νέας παρουσίας του FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθήκη άλλων τριών γραμματοσειρών στον κανόνα 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (χωρισμένα με κόμμα) για FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Λαμβάνει τον πρώτο δείκτη του συνεχούς εύρους Unicode.

**Επιστρέφει:**
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Λαμβάνει τον τελευταίο δείκτη του συνεχούς εύρους Unicode.

**Επιστρέφει:**
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό των γραμματοσειρών που ορίζονται πραγματικά για το εύρος.

**Επιστρέφει:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Λαμβάνει το όνομα της γραμματοσειράς στο καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις γραμματοσειρές από τη λίστα.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.

--------------------

> ```
> // Δημιουργία κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Αφαίρεση του Tahoma από τη λίστα
>  newRule.remove("Tahoma");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα αφαιρεθεί από τη λίστα. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί τη γραμματοσειρά FallBack στο καθορισμένο δείκτη της λίστας.

--------------------

> ```
> // Δημιουργία κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Αφαίρεση του Tahoma από τη λίστα
>  newRule.remove(2);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης της γραμματοσειράς που θα αφαιρεθεί. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα.

--------------------

> ```
> // Δημιουργία κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Λήψη όλων των ονομάτων γραμματοσειρών ως πίνακα
>  String[] fontNames = newRule.toArray();
> ```

**Επιστρέφει:**
java.lang.String[] - Πίνακας τύπου String

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από το καθορισμένο εύρος στη λίστα.

--------------------

> ```
> // Δημιουργία κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Λήψη των τελευταίων δύο ονομάτων γραμματοσειρών ως πίνακα
>  String[] fontNames = newRule.toArray(2,2);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Δείκτης της πρώτης γραμματοσειράς που θα προσθέσει. |
| count | int | Αριθμός γραμματοσειρών προς προσθήκη. |

**Επιστρέφει:**
java.lang.String[] - Πίνακας τύπου String

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Επιστρέφει έναν δείκτη του καθορισμένου κανόνα στη συλλογή.

--------------------

> ```
> // Δημιουργία κανόνα που περιέχει λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Λήψη δείκτη του Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που θα βρεθεί. |

**Επιστρέφει:**
int - Δείκτης μιας γραμματοσειράς ή -1 αν η γραμματοσειρά δεν βρεθεί στη λίστα.