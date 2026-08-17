---
title: MathDelimiter
second_title: Aspose.Slides για Java – Αναφορά API
description: Καθορίζει το αντικείμενο οριοθέτη που αποτελείται από χαρακτήρες ανοίγματος και κλεισίματος όπως παρενθέσεις, άγκιστρα, αγκύλες και κατακόρυφες γραμμές, καθώς και ένα ή περισσότερα μαθηματικά στοιχεία μέσα του, χωρισμένα με έναν καθορισμένο χαρακτήρα.
type: docs
url: /el/com.aspose.slides/mathdelimiter/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Καθορίζει το αντικείμενο οριοθέτη, που αποτελείται από χαρακτήρες έναρξης και λήξης (όπως παρενθέσεις, άγκιστρα, αγκύλες και κατακόρυφες γραμμές) και ένα ή περισσότερα μαθηματικά στοιχεία μέσα, χωρισμένα με έναν καθορισμένο χαρακτήρα. Παραδείγματα: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτη |
| [getBeginningCharacter()](#getBeginningCharacter--) | Ο χαρακτήρας αρχής του οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Ο χαρακτήρας αρχής του οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Ο χαρακτήρας διαχωριστή του οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Ο χαρακτήρας διαχωριστή του οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. |
| [getEndingCharacter()](#getEndingCharacter--) | Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Καθορίζει την αύξηση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες αυξάνονται κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Καθορίζει την αύξηση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες αυξάνονται κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. |
| [getDelimiterShape()](#getDelimiterShape--) | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Κλείνει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [getChildren()](#getChildren--) | Λαμβάνει τα παιδικά στοιχεία |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες Χαρακτήρα Ελέγχου |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Το βασικό στοιχείο στο οποίο εφαρμόζεται ο οριοθέτης. Μπορεί να είναι null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτη

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

Ο χαρακτήρας αρχής του οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: '('.

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

Ο χαρακτήρας αρχής του οριοθέτη καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: '('.

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

Ο χαρακτήρας διαχωριστή του οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. Η προεπιλογή: '|'.

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

Ο χαρακτήρας διαχωριστή του οριοθέτη καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο οριοθέτη. Η προεπιλογή: '|'.

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

Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: ')'.

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

Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό, ή κλειστό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: ')'.

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

Καθορίζει την αύξηση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες αυξάνονται κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλογή είναι true

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

Καθορίζει την αύξηση των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι οριοθέτες αυξάνονται κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλογή είναι true

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

Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες κεντρώνονται γύρω από τον άξονα των μαθηματικών κειμένων και εξακολουθούν να προσαρμόζονται στο συνολικό ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

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

Καθορίζει το σχήμα των οριοθετών στο αντικείμενο οριοθέτη. Όταν είναι MathDelimiterShape.Centered, οι οριοθέτες κεντρώνονται γύρω από τον άξονα των μαθηματικών κειμένων και εξακολουθούν να προσαρμόζονται στο συνολικό ύψος του περιεχομένου τους. Όταν είναι MathDelimiterShape.Match, το ύψος και το σχήμα τους τροποποιούνται ώστε να ταιριάζουν ακριβώς με το περιεχόμενό τους.

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

Οριοθετεί τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | χαρακτήρας οριοθέτη |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Αυτό το αντικείμενο μετά την εφαρμογή του χαρακτήρα οριοθέτη
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Κλείνει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

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
| beginningCharacter | char | Χαρακτήρας αρχής (συνήθως αριστερό αγκύλη) |
| endingCharacter | char | Χαρακτήρας λήξης (συνήθως δεξί αγκύλη) |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Αν beginningCharacter και endingCharacter είναι null, οι αντίστοιχες ιδιότητες ανατίθενται τιμές μόνο και δεν δημιουργείται νέο αντικείμενο (επιστρέφει αυτήν την περίπτωση). Διαφορετικά, επιστρέφει νέο μαθηματικό στοιχείο τύπου Delimiter που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και αυτήν την περίπτωση του [MathDelimiter](../../com.aspose.slides/mathdelimiter) περικυκλωμένο μέσα.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Λαμβάνει τα παιδικά στοιχεία

**Επιστρέφει:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Ιδιότητες Χαρακτήρα Ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps