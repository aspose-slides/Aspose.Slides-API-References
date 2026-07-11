---
title: IFontFallBackRule
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει τον κανόνα εναλλακτικής γραμματοσειράς
type: docs
url: /el/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Αντιπροσωπεύει τον κανόνα εναλλακτικής γραμματοσειράς
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Προσθέτει νέα γραμματοσειρά(-ές) στη λίστα των γραμματοσειρών FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Προσθέτει νέα γραμματοσειρά(-ές) στη λίστα των γραμματοσειρών FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Λαμβάνει το πρώτο ευρετήριο του συνεχούς εύρους Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Λαμβάνει το τελευταίο ευρετήριο του συνεχούς εύρους Unicode. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό των γραμματοσειρών που έχουν οριστεί για το εύρος. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το όνομα της γραμματοσειράς στο συγκεκριμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλες τις γραμματοσειρές από τη λίστα. |
| [remove(String fontName)](#remove-java.lang.String-) | Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί τη γραμματοσειρά FallBack στο συγκεκριμένο ευρετήριο στη λίστα. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από το καθορισμένο εύρος στη λίστα. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Επιστρέφει ένα ευρετήριο του συγκεκριμένου κανόνα στη συλλογή. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Προσθέτει νέα γραμματοσειρά(-ές) στη λίστα των γραμματοσειρών FallBack.

--------------------

> ```
> //Δημιουργία νέου αντικειμένου FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθήκη δεύτερης γραμματοσειράς στον κανόνα 
>  newRule.addFallBackFonts("MS Gothic");
>  //Προσθήκη τρίτης και τέταρτης γραμματοσειράς στον κανόνα 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Προσθέτει νέα γραμματοσειρά(-ές) στη λίστα των γραμματοσειρών FallBack.

--------------------

> ```
> //Δημιουργία νέου αντικειμένου FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Προσθήκη άλλων τριών γραμματοσειρών στον κανόνα 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | java.lang.String[] | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Λαμβάνει το πρώτο ευρετήριο του συνεχούς εύρους Unicode.

**Επιστρέφει:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Λαμβάνει το τελευταίο ευρετήριο του συνεχούς εύρους Unicode.

**Επιστρέφει:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Αποκτά τον αριθμό των γραμματοσειρών που έχουν οριστεί για το εύρος.

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Αποκτά το όνομα της γραμματοσειράς στο συγκεκριμένο ευρετήριο.

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

Αφαιρέτει την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.

--------------------

> ```
> // Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
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

Αφαιρεί τη γραμματοσειρά FallBack στο συγκεκριμένο ευρετήριο στη λίστα.

--------------------

> ```
> // Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Αφαίρεση του Tahoma από τη λίστα
>  newRule.remove(2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό-βάση ευρετήριο της γραμματοσειράς που θα αφαιρεθεί. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα.

--------------------

> ```
> // Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Λαμβάνει όλα τα ονόματα γραμματοσειρών ως πίνακα
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
> // Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Λαμβάνει τις τελευταίες δύο ονομασίες γραμματοσειρών ως πίνακα
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Ένα ευρετήριο της πρώτης γραμματοσειράς που θα προστεθεί. |
| count | int | Αριθμός γραμματοσειρών που θα προστεθούν. |

**Επιστρέφει:**
java.lang.String[] - Πίνακας τύπου String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Επιστρέφει ένα ευρετήριο του συγκεκριμένου κανόνα στη συλλογή.

--------------------

> ```
> // Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Λαμβάνει το ευρετήριο του Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το όνομα της γραμματοσειράς που πρέπει να βρεθεί. |

**Επιστρέφει:**
int - Ευρετήριο μιας γραμματοσειράς ή -1 αν η γραμματοσειρά δεν βρεθεί στη λίστα.