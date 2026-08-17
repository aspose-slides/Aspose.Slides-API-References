---
title: MathElementBase
second_title: Aspose.Slides για την Αναφορά του Java API
description: Βασική κλάση για το IMathElement με την υλοποίηση ορισμένων μεθόδων που είναι κοινές σε όλες τις κληματικές κλάσεις. Μόνο για εσωτερική χρήση.
type: docs
url: /el/com.aspose.slides/mathelementbase/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Βάση κλάση για IMathElement με την υλοποίηση ορισμένων μεθόδων που είναι κοινές σε όλες τις κληρονομικές κλάσεις. Για εσωτερική χρήση μόνο. Η κληρονομική κλάση πρέπει να είναι IMathElement.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Επιστρέφει το αντικείμενο Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [join(String mathText)](#join-java.lang.String-) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [divide(String denominator)](#divide-java.lang.String-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [enclose()](#enclose--) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [function(String functionArgument)](#function-java.lang.String-) | Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Δημιουργεί δείκτη |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Δημιουργεί δείκτη |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Δημιουργεί εκθέτη |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Δημιουργεί εκθέτη |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Δημιουργεί υποδείκτη και εκθέτη στα δεξιά |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Δημιουργεί υποδείκτη και εκθέτη στα αριστερά |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [radical(String degree)](#radical-java.lang.String-) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Πάρει άνω όριο |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Πάρει άνω όριο |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Πάρει κάτω όριο |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Πάρει κάτω όριο |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί έναν N-άριθμο τελεστή |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Δημιουργεί έναν N-άριθμο τελεστή |
| [toMathArray()](#toMathArray--) | Τοποθετεί σε κατακόρυφη σειρά |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Πάρει το ολοκλήρωμα |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Πάρει το ολοκλήρωμα |
| [integral(int integralType)](#integral-int-) | Πάρει το ολοκλήρωμα χωρίς όρια |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Πάρει το ολοκλήρωμα |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Πάρει το ολοκλήρωμα |
| [accent(char accentCharacter)](#accent-char-) | Ορίζει ένα διακριτικό (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [overbar()](#overbar--) | Τοποθετεί μια γραμμή πάνω από αυτό το στοιχείο |
| [underbar()](#underbar--) | Τοποθετεί μια γραμμή κάτω από αυτό το στοιχείο |
| [group()](#group--) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως κάτω αγκύλη ή άλλο |
| [toBorderBox()](#toBorderBox--) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο περιγράμματος |
| [toBox()](#toBox--) | Τοποθετεί αυτό το στοιχείο σε μη οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για την ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης αναπαράστασης μαθηματικού κειμένου. |
| [getChildren()](#getChildren--) | Λήψη των στοιχείων παιδιών |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. IDOMObject μόνο για ανάγνωση.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Το στοιχείο που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτήν την παρουσία και το καθορισμένο όρισμα

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathText | java.lang.String | Μαθηματικό κείμενο για σύνδεση |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτήν την παρουσία και το καθορισμένο όρισμα

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρονομαστής |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | java.lang.String | Παρονομαστής |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρονομαστής |
| fractionType | int | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| denominator | java.lang.String | Παρονομαστής |
| fractionType | int | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τις παρενθέσεις

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες, όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

**Επιστρέφει:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Ένα όρισμα της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Δημιουργεί μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionArgument | java.lang.String | Ένα όρισμα της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Όνομα συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | java.lang.String | Όνομα συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | int | Ένας από τους συνηθισμένους τύπους συνάρτησης ενός ορίσματος |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | int | Ένας από τους συνηθισμένους τύπους συνάρτησης δύο ορίσματα: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Επιπλέον όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Πάρει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και καθορισμένο επιπλέον όρισμα

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | int | Ένας από τους συνηθισμένους τύπους συνάρτησης δύο ορίσματα: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Επιπλέον όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Δημιουργεί δείκτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κάτω δείκτης δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Δημιουργεί δείκτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κάτω δείκτης δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Δημιουργεί εκθέτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (άνω δείκτης δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Δημιουργεί εκθέτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| superscript | java.lang.String | Εκθέτης (άνω δείκτης δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Δημιουργεί υποδείκτη και εκθέτη στα δεξιά

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κάτω δείκτης δεξιά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (άνω δείκτης δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κάτω δείκτης στα δεξιά) |
| superscript | java.lang.String | Εκθέτης (πάνω δείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Δημιουργεί δείκτη υποσυνόλου και εκθέτη στα αριστερά

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κάτω δείκτης στα αριστερά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (πάνω δείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Δημιουργεί δείκτη υποσυνόλου και εκθέτη στα αριστερά

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κάτω δείκτης στα αριστερά) |
| superscript | java.lang.String | Εκθέτης (πάνω δείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα.

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Όρισμα του Ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέα παρουσία τύπου [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα.

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | java.lang.String | Όρισμα του Ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέα παρουσία τύπου [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Παίρνει άνω όριο

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Παίρνει άνω όριο

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | java.lang.String | όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Παίρνει κάτω όριο

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Παίρνει κάτω όριο

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Δημιουργεί έναν N-ary τελεστή

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του N-ary τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Το κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Το άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Δημιουργεί έναν N-ary τελεστή

---

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του N-ary τελεστή |
| lowerLimit | java.lang.String | Το κάτω όριο |
| upperLimit | java.lang.String | Το άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Τοποθετεί σε κατακόρυφο πίνακα

---

> ```
> Παράδειγμα:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Επιστρέφει:**
[IMathArray](../../com.aspose.slides/imatharray) - Νέα παρουσία τύπου [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Παίρνει το ολοκλήρωμα

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο του ολοκληρώματος |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο του ολοκληρώματος |
| limitLocations | int | Θέση των ορίων |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Παίρνει το ολοκλήρωμα

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο του ολοκληρώματος |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο του ολοκληρώματος |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Παίρνει το ολοκλήρωμα χωρίς όρια

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Παίρνει το ολοκλήρωμα

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |
| lowerLimit | java.lang.String | Κάτω όριο του ολοκληρώματος |
| upperLimit | java.lang.String | Άνω όριο του ολοκληρώματος |
| limitLocations | int | Θέση των ορίων |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Παίρνει το ολοκλήρωμα

---

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |
| lowerLimit | java.lang.String | Κάτω όριο του ολοκληρώματος |
| upperLimit | java.lang.String | Άνω όριο του ολοκληρώματος |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα πάνω σε αυτό το στοιχείο)

---

> ```
> Παράδειγμα:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| accentCharacter | char | Χαρακτήρας τονισμού. Η τιμή πρέπει να είναι εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Νέα παρουσία τύπου [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου

---

> ```
> Παράδειγμα:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέα παρουσία τύπου [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου

---

> ```
> Παράδειγμα:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέα παρουσία τύπου [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω καμπυλωτή αγκύλη

---

> ```
> Παράδειγμα:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέα παρουσία τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω καμπυλωτή αγκύλη ή άλλον

---

> ```
> Παράδειγμα:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| character | char | Χαρακτήρας ομαδοποίησης όπως η BOTTOM CURLY BRACKET (U+23DF) ή οποιοσδήποτε άλλος |
| position | int | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | int | Κατακόρυφη ευθυγράμμιση του χαρακτήρα ομαδοποίησης. Καθορίζει τη στοίχιση του αντικειμένου σε σχέση με τη βάση. Για παράδειγμα, όταν ο χαρακτήρας ομαδοποίησης είναι πάνω από το αντικείμενο, η VerticalJustification της Top σημαίνει ότι η κορυφή του αντικειμένου πέφτει στη βάση· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη βάση |

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέα παρουσία τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Τοποθετεί αυτό το στοιχείο σε ένα border-box

---

> ```
> Παράδειγμα:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box με αυτό το στοιχείο τοποθετημένο μέσα
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Τοποθετεί αυτό το στοιχείο σε ένα border-box

---

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hideTop | boolean | Απόκρυψη άνω άκρου |
| hideBottom | boolean | Απόκρυψη κάτω άκρου |
| hideLeft | boolean | Απόκρυψη αριστερού άκρου |
| hideRight | boolean | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box με αυτό το στοιχείο τοποθετημένο μέσα
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Τοποθετεί αυτό το στοιχείο σε ένα non-visual box (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλου κειμένου μαθηματικού τύπου. Ένα boxed αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως προσομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο απογώνιας γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπει απογώνιες γραμμές εντός.

---

> ```
> Παράδειγμα:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Επιστρέφει:**
[IMathBox](../../com.aspose.slides/imathbox) - Λογικό κουτί με αυτό το στοιχείο τοποθετημένο μέσα
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Λαμβάνει στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)