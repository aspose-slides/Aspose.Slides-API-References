---
title: MathDelimiter
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Καθορίζει το αντικείμενο delimiter που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος όπως παρενθέσεις, αγκύλες, τετράγωνα αγκύλες και κατακόρυφες γραμμές και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, διαχωρισμένα με έναν καθορισμένο χαρακτήρα.
type: docs
url: /el/com.aspose.slides/mathdelimiter/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Καθορίζει το αντικείμενο delimiter, που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος (όπως παρενθέσεις, αγκύλες, τετράγωνα αγκύλες και κατακόρυφες γραμμές), και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, διαχωρισμένα με καθορισμένο χαρακτήρα. Παραδείγματα: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό όρισμα |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getArguments()](#getArguments--) | Ένα ή περισσότερα μαθηματικά στοιχεία διαχωρισμένα με χαρακτήρες delimiter |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ο χαρακτήρας έναρξης delimiter καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα delimiter. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ο χαρακτήρας έναρξης delimiter καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα delimiter. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ο χαρακτήρας διαχωριστικού delimiter καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ο χαρακτήρας διαχωριστικού delimiter καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. |
| [getEndingCharacter()](#getEndingCharacter--) | Ο χαρακτήρας τερματισμού delimiter καθορίζει τον τελικό, ή κλειστό, χαρακτήρα delimiter. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ο χαρακτήρας τερματισμού delimiter καθορίζει τον τελικό, ή κλειστό, χαρακτήρα delimiter. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Καθορίζει την επέκταση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Καθορίζει την επέκταση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή. |
| [getDelimiterShape()](#getDelimiterShape--) | Καθορίζει το σχήμα των delimiters στο αντικείμενο delimiter. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Καθορίζει το σχήμα των delimiters στο αντικείμενο delimiter. |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα delimiter |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Τυλίγει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα |
| [getChildren()](#getChildren--) | Παίρνει τα θυγατρικά στοιχεία |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```


Αρχικοποιεί το MathDelimiter με το καθορισμένο στοιχείο ως μοναδικό βασικό όρισμα

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται ο delimiter. Μπορεί να είναι null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```


Ένα ή περισσότερα μαθηματικά στοιχεία διαχωρισμένα με χαρακτήρες delimiter

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
public final char getBeginningCharacter()
```


Ο χαρακτήρας έναρξης delimiter καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα delimiter. Οι μαθηματικοί delimiters είναι χαρακτήρες όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: '('.

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
public final void setBeginningCharacter(char value)
```


Ο χαρακτήρας έναρξης delimiter καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα delimiter. Οι μαθηματικά delimiters είναι χαρακτήρες όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: '('.

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
public final char getSeparatorCharacter()
```


Ο χαρακτήρας διαχωριστικού delimiter καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'.

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
public final void setSeparatorCharacter(char value)
```


Ο χαρακτήρας διαχωριστικού delimiter καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'.

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
public final char getEndingCharacter()
```


Ο χαρακτήρας τερματισμού delimiter καθορίζει τον τελικό, ή κλειστό, χαρακτήρα delimiter. Οι μαθηματικοί delimiters είναι χαρακτήρες όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: ')'.

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
public final void setEndingCharacter(char value)
```


Ο χαρακτήρας τερματισμού delimiter καθορίζει τον τελικό, ή κλειστό, χαρακτήρα delimiter. Οι μαθηματικοί delimiters είναι χαρακτήρες όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλογή: ')'.

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
public final boolean getGrowToMatchOperandHeight()
```


Καθορίζει την επέκταση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή. Η προεπιλεγμένη τιμή είναι true

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
public final void setGrowToMatchOperandHeight(boolean value)
```


Καθορίζει την επέκταση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή. Η προεπιλεγμένη τιμή είναι true

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
public final int getDelimiterShape()
```


Καθορίζει το σχήμα των delimiters στο αντικείμενο delimiter. Όταν είναι MathDelimiterShape.Centered, τα delimiters κεντρώνονται γύρω από τον μαθηματικό άξονα του κειμένου και μπορούν να προσαρμοστούν ώστε να ταιριάζουν με το πλήρες ύψος των περιεχομένων τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με τα περιεχόμενά τους.

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
public final void setDelimiterShape(int value)
```


Καθορίζει το σχήμα των delimiters στο αντικείμενο delimiter. Όταν είναι MathDelimiterShape.Centered, τα delimiters κεντρώνονται γύρω από τον μαθηματικό άξονα του κειμένου και μπορούν να προσαρμοστούν ώστε να ταιριάζουν με το πλήρες ύψος των περιεχομένων τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με τα περιεχόμενά τους.

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
public final IMathDelimiter delimit(char separatorCharacter)
```


Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα delimiter

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | χαρακτήρας delimiter |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Αυτό το αντικείμενο μετά την εφαρμογή του χαρακτήρα delimiter
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Τυλίγει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Εάν beginningCharacter και endingCharacter είναι null, οι αντίστοιχες ιδιότητες αποκτούν τιμές μόνο και δεν δημιουργείται νέο αντικείμενο (επιστρέφει αυτήν την παρουσία). Διαφορετικά, επιστρέφει νέο μαθηματικό στοιχείο τύπου Delimiter που περιλαμβάνει τους καθορισμένους χαρακτήρες ως περιτύλιγμα και αυτήν την παρουσία του [MathDelimiter](../../com.aspose.slides/mathdelimiter) περιτυλιγμένη μέσα.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Παίρνει τα θυγατρικά στοιχεία

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες χαρακτήρα ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps