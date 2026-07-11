---
title: IMathBlock
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή.
type: docs
url: /el/com.aspose.slides/imathblock/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Καθορίζει ένα στιγμιότυπο μαθηματικού κειμένου που περιέχεται σε ένα MathParagraph και ξεκινά σε ξεχωριστή γραμμή. Όλες οι μαθηματικές ζώνες, συμπεριλαμβανομένων εξισώσεων, εκφράσεων, πινάκων εξισώσεων ή εκφράσεων και τύπων, αναπαρίστανται από μπλοκ μαθηματικών.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Μέθοδοι

| Method | Description |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Οριοθετεί όλα τα θυγατρικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Περιβάλλει τα θυγατρικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους, ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Συνδέει ένα άλλο μαθηματικό μπλοκ με αυτό |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο αυτού του [IMathBlock](../../com.aspose.slides/imathblock) ως MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Οριοθετεί όλα τα θυγατρικά στοιχεία με χαρακτήρα διαχωριστή (χωρίς τις αγκύλες)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char | Χαρακτήρας που χρησιμοποιείται ως διαχωριστικό |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Αντικείμενο τύπου IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Περιβάλλει τα θυγατρικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους, ως πλαίσιο και οριοθετεί με χαρακτήρα διαχωριστή

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |
| separatorCharacter | char | Χαρακτήρας διαχωρισμού |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και διαχωριστικό
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Συνδέει ένα άλλο μαθηματικό μπλοκ με αυτό

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Το μπλοκ που συνδέεται |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - αυτό το μαθηματικό μπλοκ μετά τη συγχώνευση
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο αυτού του [IMathBlock](../../com.aspose.slides/imathblock) ως MathML

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |