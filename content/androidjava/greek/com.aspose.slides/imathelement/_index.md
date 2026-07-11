---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: Βασική διεπαφή οποιουδήποτε μαθηματικού στοιχείου: κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλά στοιχεία κ.λπ.
type: docs
url: /el/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

Βασική διεπαφή οποιουδήποτε μαθηματικού στοιχείου: κλάσμα, μαθηματικό κείμενο, συνάρτηση, έκφραση με πολλά στοιχεία κ.λπ.

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία παιδιών |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [join(String mathText)](#join-java.lang.String-) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [divide(String denominator)](#divide-java.lang.String-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και τον καθορισμένο παρονομαστή |
| [enclose()](#enclose--) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Περιβάλλει αυτό το στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την περίπτωση ως όνομα συνάρτησης |
| [function(String functionArgument)](#function-java.lang.String-) | Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την περίπτωση ως όνομα συνάρτησης |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα και καθορισμένο πρόσθετο όρισμα |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Δημιουργεί δείκτη |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Δημιουργεί δείκτη |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Δημιουργεί εκθέτη |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Δημιουργεί εκθέτη |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Δημιουργεί δείκτη και εκθέτη στα δεξιά |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Δημιουργεί δείκτη και εκθέτη στα αριστερά |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [radical(String degree)](#radical-java.lang.String-) | Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Παίρνει το άνω όριο |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Παίρνει το άνω όριο |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Παίρνει το κάτω όριο |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Παίρνει το κάτω όριο |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί έναν N-αρι τελεστή |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Δημιουργεί έναν N-αρι τελεστή |
| [toMathArray()](#toMathArray--) | Τοποθετεί σε κατακόρυφη διάταξη |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Παίρνει το ολοκλήρωμα |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Παίρνει το ολοκλήρωμα |
| [integral(int integralType)](#integral-int-) | Παίρνει το ολοκλήρωμα χωρίς όρια |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Παίρνει το ολοκλήρωμα |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Παίρνει το ολοκλήρωμα |
| [accent(char accentCharacter)](#accent-char-) | Ορίζει ένα σημάδι τόνου (χαρακτήρας στην κορυφή αυτού του στοιχείου) |
| [overbar()](#overbar--) | Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου |
| [underbar()](#underbar--) | Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου |
| [group()](#group--) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη ή άλλος |
| [toBorderBox()](#toBorderBox--) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο |
| [toBox()](#toBox--) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίασης μαθηματικού κειμένου. |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

Λαμβάνει τα στοιχεία παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
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
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτή την περίπτωση και το καθορισμένο όρισμα

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
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
| mathText | java.lang.String | Μαθηματικό κείμενο που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτή την περίπτωση και το καθορισμένο όρισμα

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρανομαστής |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

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
| denominator | java.lang.String | Παρανομαστής |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
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
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρανομαστής |
| fractionType | int | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
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
| denominator | java.lang.String | Παρανομαστής |
| fractionType | int | Τύπος κλάσματος: Bar, NoBar, Skewed, Linear |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - νέο κλάσμα

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
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
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Περιβάλλει αυτό το στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαισίωση

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαισίωση

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την περίπτωση ως όνομα συνάρτησης

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
public abstract IMathFunction function(String functionArgument)
```

Παίρνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτή την περίπτωση ως όνομα συνάρτησης

--------------------

> ```
> Παράδειγμα:
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
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα

--------------------

> ```
> Example:
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
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα

--------------------

> ```
> Example:
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
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | int | Ένας από τους κοινά τύπους συνάρτησης ενός ορίσματος |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα και καθορισμένο πρόσθετο όρισμα

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
| functionType | int | Ένας από τους κοινά τύπους συνάρτησης δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Παίρνει καθορισμένη συνάρτηση χρησιμοποιώντας αυτή την περίπτωση ως όρισμα και καθορισμένο πρόσθετο όρισμα

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
| functionType | int | Ένας από τους κοινά τύπους συνάρτησης δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κατώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

Δημιουργεί δείκτη

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κατώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (ανώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

Δημιουργεί εκθέτη

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| superscript | java.lang.String | Εκθέτης (ανώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Δημιουργεί δείκτη και εκθέτη στα δεξιά

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κατώτερη υποδείκτης στα δεξιά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (ανώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Δημιουργεί δείκτη και εκθέτη στα δεξιά

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κατώτερη υποδείκτης στα δεξιά) |
| superscript | java.lang.String | Εκθέτης (ανώτερη υποδείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Δημιουργεί δείκτη και εκθέτη στα αριστερά

--------------------

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Δείκτης (κατώτερη υποδείκτης στα αριστερά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Εκθέτης (ανώτερη υποδείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Δημιουργεί δείκτη και εκθέτη στα αριστερά

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Δείκτης (κατώτερη υποδείκτης στα αριστερά) |
| superscript | java.lang.String | Εκθέτης (ανώτερη υποδείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Όρισμα του ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέα παρουσία τύπου [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

Καθορίζει τη μαθηματική ρίζα του δεδομένου βαθμού από το καθορισμένο όρισμα.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| degree | java.lang.String | Όρισμα του ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέα παρουσία τύπου [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

Παίρνει το άνω όριο

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

Παίρνει το άνω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | java.lang.String | Όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

Παίρνει το κάτω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

Παίρνει το κάτω όριο

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| limit | java.lang.String | Όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέα παρουσία τύπου [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Δημιουργεί έναν N-αρι τελεστή

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του N-αρι τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Το κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Το άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Δημιουργεί έναν N-αρι τελεστή

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του N-αρι τελεστή |
| lowerLimit | java.lang.String | Το κάτω όριο |
| upperLimit | java.lang.String | Το άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

Τοποθετεί σε κατακόρυφη διάταξη

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Επιστρέφει:**
[IMathArray](../../com.aspose.slides/imatharray) - Νέα παρουσία τύπου [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Παίρνει το ολοκλήρωμα

--------------------

> ```
> Example:
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
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Παίρνει το ολοκλήρωμα

--------------------

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
public abstract IMathNaryOperator integral(int integralType)
```

Παίρνει το ολοκλήρωμα χωρίς όρια

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέα παρουσία τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Παίρνει το ολοκλήρωμα

--------------------

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
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Παίρνει το ολοκλήρωμα

--------------------

> ```
> Example:
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
public abstract IMathAccent accent(char accentCharacter)
```

Ορίζει ένα σημάδι τόνου (χαρακτήρας στην κορυφή αυτού του στοιχείου)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| accentCharacter | char | Χαρακτήρας τόνου. Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Νέα παρουσία τύπου [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

Τοποθετεί μια γραμμή στην κορυφή αυτού του στοιχείου

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέα παρουσία τύπου [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

Τοποθετεί μια γραμμή στο κάτω μέρος αυτού του στοιχείου

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέα παρουσία τύπου [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας μια κάτω αγκύλη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέα παρουσία τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης, όπως η κάτω αγκύλη ή άλλος

--------------------

> ```
> Παράδειγμα:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| character | char | Χαρακτήρας ομαδοποίησης, όπως ΚΑΤΩ ΑΓΚΥΛΗ (U+23DF) ή άλλος |
| position | int | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | int | Κάθετη ευθυγράμμιση του χαρακτήρα ομάδας. Προσδιορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη βάση. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η Κάθετη Ευθυγράμμιση Top σημαίνει ότι το πάνω μέρος του αντικειμένου βρίσκεται στη βάση· όταν η Κάθετη Ευθυγράμμιση είναι Bottom, το κάτω μέρος του αντικειμένου είναι στη βάση. |

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέα παρουσία τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
```

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Πλαίσιο-περιθώριο με αυτό το στοιχείο τοποθετημένο μέσα

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Τοποθετεί αυτό το στοιχείο σε πλαίσιο-περιθώριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hideTop | boolean | Απόκρυψη πάνω άκρου |
| hideBottom | boolean | Απόκρυψη κάτω άκρου |
| hideLeft | boolean | Απόκρυψη αριστερού άκρου |
| hideRight | boolean | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | boolean | Γραμμή διαγράμματος οριζόντια στο πλαίσιο |
| strikethroughVertical | boolean | Γραμμή διαγράμματος κάθετη στο πλαίσιο |
| strikethroughBottomLeftToTopRight | boolean | Γραμμή διαγράμματος από κάτω αριστερά προς πάνω δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Γραμμή διαγράμματος από πάνω αριστερά προς κάτω δεξιά |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Πλαίσιο-περιθώριο με αυτό το στοιχείο τοποθετημένο μέσα

### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για ομαδοποίηση στοιχείων μιας εξίσωσης ή άλλης παρουσίασης μαθηματικού κειμένου. Ένα αντικείμενο σε κουτί μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να λειτουργήσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπει αλλαγές γραμμής εντός.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Επιστρέφει:**
[IMathBox](../../com.aspose.slides/imathbox) - Λογικό κουτί με αυτό το στοιχείο τοποθετημένο μέσα