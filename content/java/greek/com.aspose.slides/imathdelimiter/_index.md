---
title: IMathDelimiter
second_title: Αναφορά API του Aspose.Slides για Java
description: Καθορίζει το αντικείμενο οριοθέτη που αποτελείται από ανοιχτικούς και κλειστούς χαρακτήρες όπως παρενθέσεις, αγκύλες, τετράγωνα αγκύλες και κατακόρυφες γραμμές, καθώς και ένα ή περισσότερα μαθηματικά στοιχεία μέσα που χωρίζονται με έναν καθορισμένο χαρακτήρα.
type: docs
url: /el/com.aspose.slides/imathdelimiter/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Καθορίζει το αντικείμενο οριοθέτη, που αποτελείται από ανοιγόμενους και κλειστούς χαρακτήρες (όπως παρενθέσεις, αγκύλες, άγκιστρα και κατακόρυφες γραμμές), και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με έναν καθορισμένο χαρακτήρα. Παραδείγματα: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArguments()](#getArguments--) | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτη. |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ο Χαρακτήρας Έναρξης Οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ο Χαρακτήρας Έναρξης Οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ο Χαρακτήρας Διαχωριστή Οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο οριοθέτη. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ο Χαρακτήρας Διαχωριστή Οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο οριοθέτη. |
| [getEndingCharacter()](#getEndingCharacter--) | Ο Χαρακτήρας Λήξης Οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ο Χαρακτήρας Λήξης Οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Καθορίζει την επέκταση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Καθορίζει την επέκταση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. |
| [getDelimiterShape()](#getDelimiterShape--) | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί τα επιχειρήματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτη.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Επιστρέφει:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Ο Χαρακτήρας Έναρξης Οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθέτες είναι περιβάλλοντες χαρακτήρες όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλεγμένη τιμή: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Επιστρέφει:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Ο Χαρακτήρας Έναρξης Οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθέτες είναι περιβάλλοντες χαρακτήρες όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλεγμένη τιμή: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Ο Χαρακτήρας Διαχωριστή Οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο οριοθέτη. Η προεπιλεγμένη τιμή: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Επιστρέφει:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Ο Χαρακτήρας Διαχωριστή Οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο οριοθέτη. Η προεπιλεγμένη τιμή: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Ο Χαρακτήρας Λήξης Οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθέτες είναι περιβάλλοντες χαρακτήρες όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλεγμένη τιμή: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Επιστρέφει:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Ο Χαρακτήρας Λήξης Οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθέτες είναι περιβάλλοντες χαρακτήρες όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλεγμένη τιμή: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Καθορίζει την επέκταση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Επιστρέφει:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Καθορίζει την επέκταση των χαρακτήρων BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες κεντρώνονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και προσαρμόζονται ώστε να ταιριάζουν με το πλήρες ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Επιστρέφει:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες κεντρώνονται γύρω από τον μαθηματικό άξονα του μαθηματικού κειμένου και προσαρμόζονται ώστε να ταιριάζουν με το πλήρες ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Οριοθετεί τα επιχειρήματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | χαρακτήρας οριοθέτη |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Αυτό το αντικείμενο μετά την εφαρμογή του χαρακτήρα οριοθέτη