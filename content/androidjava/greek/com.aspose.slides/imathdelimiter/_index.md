---
title: IMathDelimiter
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Καθορίζει το αντικείμενο διαχωριστή που αποτελείται από χαρακτήρες έναρξης και λήξης, όπως παρενθέσεις, άγκιστρα, αγκύλες και κάθετες γραμμές, καθώς και ένα ή περισσότερα μαθηματικά στοιχεία μέσα που χωρίζονται με έναν καθορισμένο χαρακτήρα.
type: docs
url: /el/com.aspose.slides/imathdelimiter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Καθορίζει το αντικείμενο διαχωριστή, που αποτελείται από χαρακτήρες άνοιγμα και κλείσιμο (όπως παρενθέσεις, άγκιστρα, αγκύλες και κάθετες γραμμές) και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με έναν καθορισμένο χαρακτήρα. Παραδείγματα: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArguments()](#getArguments--) | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες διαχωριστή |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ο Χαρακτήρας Έναρξης Διαχωριστή καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστή. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ο Χαρακτήρας Έναρξης Διαχωριστή καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστή. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ο Χαρακτήρας Διαχωριστή Καθορίζει τον χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστή. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ο Χαρακτήρας Διαχωριστή Καθορίζει τον χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστή. |
| [getEndingCharacter()](#getEndingCharacter--) | Ο Χαρακτήρας Λήξης Διαχωριστή καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστή. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ο Χαρακτήρας Λήξης Διαχωριστή καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστή. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι διαχωριστές μεγαλώνουν κατακόρυφα για να ταιριάζουν στο ύψος του τελεστή. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι διαχωριστές μεγαλώνουν κατακόρυφα για να ταιριάζουν στο ύψος του τελεστή. |
| [getDelimiterShape()](#getDelimiterShape--) | Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. |
| [delimit(char separatorCharacter)](#delimit-char-) | Διαχωρίζει τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα διαχωριστή |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες διαχωριστή

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

Ο Χαρακτήρας Έναρξης Διαχωριστή καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστή. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες που περικλείουν, όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: '('.

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

Ο Χαρακτήρας Έναρξης Διαχωριστή καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα διαχωριστή. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες που περικλείουν, όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: '('.

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

Ο Χαρακτήρας Διαχωριστή Καθορίζει τον χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστή. Η προεπιλογή: '|'.

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

Ο Χαρακτήρας Διαχωριστή Καθορίζει τον χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστή. Η προεπιλογή: '|'.

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

Ο Χαρακτήρας Λήξης Διαχωριστή καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστή. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες που περικλείουν, όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: ')'.

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

Ο Χαρακτήρας Λήξης Διαχωριστή καθορίζει τον τελικό, ή κλειστό, χαρακτήρα διαχωριστή. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες που περικλείουν, όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: ')'.

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

Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι διαχωριστές μεγαλώνουν κατακόρυφα για να ταιριάζουν στο ύψος του τελεστή. Η προεπιλεγμένη τιμή είναι true

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

Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι διαχωριστές μεγαλώνουν κατακόρυφα για να ταιριάζουν στο ύψος του τελεστή. Η προεπιλεγμένη τιμή είναι true

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

Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. Όταν είναι MathDelimiterShape.Centered, οι διαχωριστές κεντρώνονται γύρω από τον μαθηματικό άξονα του κειμένου και μπορούν να προσαρμοστούν ώστε να ταιριάζουν στο συνολικό ύψος των περιεχομένων τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

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

Καθορίζει το σχήμα των διαχωριστών στο αντικείμενο διαχωριστή. Όταν είναι MathDelimiterShape.Centered, οι διαχωριστές κεντρώνονται γύρω από τον μαθηματικό άξονα του κειμένου και μπορούν να προσαρμοστούν ώστε να ταιριάζουν στο συνολικό ύψος των περιεχομένων τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

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

Διαχωρίζει τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα διαχωριστή

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
| separatorCharacter | char | χαρακτήρας διαχωριστή |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - This object after applying the delimiter character