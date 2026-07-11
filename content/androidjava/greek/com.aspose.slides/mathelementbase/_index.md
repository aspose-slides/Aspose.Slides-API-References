---
title: MathElementBase
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Βασική κλάση για το IMathElement με την υλοποίηση ορισμένων μεθόδων που είναι κοινές σε όλες τις κληρονομημένες κλάσεις. Για εσωτερική χρήση μόνο.
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

Βασική κλάση για το IMathElement με την υλοποίηση ορισμένων μεθόδων που είναι κοινές σε όλες τις κληματικές κλάσεις. Για εσωτερική χρήση μόνο. Η κληματική κλάση πρέπει να είναι το IMathElement.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Επιστρέφει το αντικείμενο Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Συνδέει ένα μαθηματικό στοιχείο και δημιουργεί ένα μαθηματικό μπλοκ |
| [join(String mathText)](#join-java.lang.String-) | Συνδέει ένα μαθηματικό κείμενο και δημιουργεί ένα μαθηματικό μπλοκ |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [divide(String denominator)](#divide-java.lang.String-) | Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή |
| [enclose()](#enclose--) | Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [function(String functionArgument)](#function-java.lang.String-) | Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και ένα καθορισμένο πρόσθετο όρισμα |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και ένα καθορισμένο πρόσθετο όρισμα |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Δημιουργεί υποδείκτη |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Δημιουργεί υποδείκτη |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Δημιουργεί υπερδείκτη |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Δημιουργεί υπερδείκτη |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί υποδείκτη και υπερδείκτη στα δεξιά |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Δημιουργεί υποδείκτη και υπερδείκτη στα δεξιά |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [radical(String degree)](#radical-java.lang.String-) | Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Λαμβάνει άνω όριο |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Λαμβάνει άνω όριο |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Λαμβάνει κάτω όριο |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Λαμβάνει κάτω όριο |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί έναν N-ary τελεστή |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Δημιουργεί έναν N-ary τελεστή |
| [toMathArray()](#toMathArray--) | Τοποθετεί σε κατακόρυφο πίνακα |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Λαμβάνει το ολοκλήρωμα |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Λαμβάνει το ολοκλήρωμα |
| [integral(int integralType)](#integral-int-) | Λαμβάνει το ολοκλήρωμα χωρίς όρια |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Λαμβάνει το ολοκλήρωμα |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Λαμβάνει το ολοκλήρωμα |
| [accent(char accentCharacter)](#accent-char-) | Ορίζει σημείο τόνου (χαρακτήρας πάνω από αυτό το στοιχείο) |
| [overbar()](#overbar--) | Τοποθετεί γραμμή πάνω από αυτό το στοιχείο |
| [underbar()](#underbar--) | Τοποθετεί γραμμή κάτω από αυτό το στοιχείο |
| [group()](#group--) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας αγκυλόμορφο στο κάτω μέρος |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως το κάτω αγκυλόμορφο ή άλλο |
| [toBorderBox()](#toBorderBox--) | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα |
| [toBox()](#toBox--) | Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για να ομαδοποιήσει τα στοιχεία μιας εξίσωσης ή άλλο μαθηματικό κείμενο. |
| [getChildren()](#getChildren--) | Λαμβάνει τα στοιχεία-παιδιά |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

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
| mathText | java.lang.String | Μαθηματικό κείμενο που θα συνδεθεί |

**Επιστρέφει:**
[IMathBlock](../../com.aspose.slides/imathblock) - Ένα νέο IMathBlock που περιέχει αυτήν την παρουσία και το καθορισμένο όρισμα
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```


Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

--------------------

> ```
> Παράδειγμα:
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


Δημιουργεί ένα κλάσμα με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

--------------------

> ```
> Παράδειγμα:
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


Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

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


Δημιουργεί ένα κλάσμα του καθορισμένου τύπου με αυτόν τον αριθμητή και το καθορισμένο παρονομαστή

--------------------

> ```
> Παράδειγμα:
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
> Παράδειγμα:
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


Περιβάλλει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα

--------------------

> ```
> Παράδειγμα:
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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../com.aspose.slides/imathdelimiter) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως περιτύλιγμα
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```


Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης

--------------------

> ```
> Παράδειγμα:
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


Λαμβάνει μια συνάρτηση ενός ορίσματος χρησιμοποιώντας αυτήν την παρουσία ως όνομα συνάρτησης

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
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```


Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

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


Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

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


Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

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
| functionType | int | Ένας από τους κοινούς τύπους συναρτήσεων ενός ορίσματος |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και ένα καθορισμένο πρόσθετο όρισμα

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
| functionType | int | Ένας από τους κοινούς τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και ένα καθορισμένο πρόσθετο όρισμα

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
| functionType | int | Ένας από τους κοινούς τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

**Επιστρέφει:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Νέο μαθηματικό στοιχείο τύπου [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```


Δημιουργεί υποδείκτη

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Υποδείκτης (χαμηλότερο δείκτη στα δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```


Δημιουργεί υποδείκτη

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
| subscript | java.lang.String | Υποδείκτης (χαμηλότερο δείκτη στα δεξιά) |

**Επιστρέφει:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


Δημιουργεί υπερδείκτη

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Υπερδείκτης (άνω δείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


Δημιουργεί υπερδείκτη

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
| superscript | java.lang.String | Υπερδείκτης (άνω δείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


Δημιουργεί υποδείκτη και υπερδείκτη στα δεξιά

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Υποδείκτης (χαμηλότερο δείκτη στα δεξιά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Υπερδείκτης (άνω δείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```


Δημιουργεί υποδείκτη και υπερδείκτη στα δεξιά

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subscript | java.lang.String | Υποδείκτης (χαμηλότερο δείκτη στα δεξιά) |
| superscript | java.lang.String | Υπερδείκτης (άνω δείκτης στα δεξιά) |

**Επιστρέφει:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά

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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Υποδείκτης (χαμηλότερο δείκτη στα αριστερά) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Υπερδείκτης (άνω δείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


Δημιουργεί υποδείκτη και υπερδείκτη στα αριστερά

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
| subscript | java.lang.String | Υποδείκτης (χαμηλότερο δείκτη στα αριστερά) |
| superscript | java.lang.String | Υπερδείκτης (άνω δείκτης στα αριστερά) |

**Επιστρέφει:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Νέο μαθηματικό στοιχείο τύπου [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```


Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Όρισμα Ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέο παράδειγμα τύπου [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```


Καθορίζει τη μαθηματική ρίζα του δοσμένου βαθμού από το καθορισμένο όρισμα.

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| degree | java.lang.String | Όρισμα Ριζικού |

**Επιστρέφει:**
[IMathRadical](../../com.aspose.slides/imathradical) - Νέο παράδειγμα τύπου [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```


Λαμβάνει άνω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | άνω όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέο παράδειγμα τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```


Λαμβάνει άνω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| limit | java.lang.String | άνω όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέο παράδειγμα τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```


Λαμβάνει κάτω όριο

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | κάτω όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέο παράδειγμα τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```


Λαμβάνει κάτω όριο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| limit | java.lang.String | κάτω όριο |

**Επιστρέφει:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Νέο παράδειγμα τύπου [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


Δημιουργεί έναν N-ary τελεστή

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
| type | int | Τύπος N-ary τελεστή |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Κάτω όριο |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


Δημιουργεί έναν N-ary τελεστή

--------------------

> ```
> Παράδειγμα:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Τύπος N-ary τελεστή |
| lowerLimit | java.lang.String | Κάτω όριο |
| upperLimit | java.lang.String | Άνω όριο |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


Τοποθετεί σε κατακόρυφο πίνακα

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Επιστρέφει:**
[IMathArray](../../com.aspose.slides/imatharray) - Νέο παράδειγμα τύπου [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


Λαμβάνει το ολοκλήρωμα

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
| limitLocations | int | θέση των ορίων |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


Λαμβάνει το ολοκλήρωμα

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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```


Λαμβάνει το ολοκλήρωμα χωρίς όρια

--------------------

> ```
> Παράδειγμα:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Παράμετρος**
| Παράμετρος | Τύπο | Περιγραφή |
| --- | --- | --- |
| integralType | int | Τύπος ολοκληρώματος |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


Λαμβάνει το ολοκλήρωμα

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
| limitLocations | int | θέση των ορίων |

**Επιστρέφει:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


Λαμβάνει το ολοκλήρωμα

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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Νέο παράδειγμα τύπου [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```


Ορίζει σημείο τόνου (χαρακτήρας πάνω από αυτό το στοιχείο)

--------------------

> ```
> Παράδειγμα:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| accentCharacter | char | Χαρακτήρας τόνου. Η τιμή πρέπει να είναι στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) |

**Επιστρέφει:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Νέο παράδειγμα τύπου [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```


Τοποθετεί γραμμή πάνω από αυτό το στοιχείο

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέο παράδειγμα τύπου [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```


Τοποθετεί γραμμή κάτω από αυτό το στοιχείο

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Επιστρέφει:**
[IMathBar](../../com.aspose.slides/imathbar) - Νέο παράδειγμα τύπου [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```


Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας αγκυλόμορφο στο κάτω μέρος

--------------------

> ```
> Παράδειγμα:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέο παράδειγμα τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


Τοποθετεί αυτό το στοιχείο σε ομάδα χρησιμοποιώντας χαρακτήρα ομαδοποίησης όπως το κάτω αγκυλόμορφο ή άλλο

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| character | char | Χαρακτήρας ομαδοποίησης όπως BOTTOM CURLY BRACKET (U+23DF) ή οποιοσδήποτε άλλος |
| position | int | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | int | Κατακόρυφη στοίχιση του χαρακτήρα ομαδοποίησης. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομαδοποίησης είναι πάνω από το αντικείμενο, η κατακόρυφη στοίχιση Top σημαίνει ότι η κορυφή του αντικειμένου πέφτει στη γραμμή βάσης· όταν η κατακόρυφη στοίχιση είναι Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης |

**Επιστρέφει:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Νέο παράδειγμα τύπου [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```


Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Κουτί-περίγραμμα με αυτό το στοιχείο τοποθετημένο μέσα
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Τοποθετεί αυτό το στοιχείο σε κουτί-περίγραμμα

--------------------

> ```
> Παράδειγμα:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hideTop | boolean | Απόκρυψη επάνω άκρου |
| hideBottom | boolean | Απόκρυψη κάτω άκρου |
| hideLeft | boolean | Απόκρυψη αριστερού άκρου |
| hideRight | boolean | Απόκρυψη δεξιού άκρου |
| strikethroughHorizontal | boolean | Διαγράμμιση οριζόντιας πλευράς του κουτιού |
| strikethroughVertical | boolean | Διαγράμμιση κάθετης πλευράς του κουτιού |
| strikethroughBottomLeftToTopRight | boolean | Διαγράμμιση διαγωνίου από κάτω-αριστερά προς πάνω-δεξιά |
| strikethroughTopLeftToBottomRight | boolean | Διαγράμμιση διαγωνίου από πάνω-αριστερά προς κάτω-δεξιά |

**Επιστρέφει:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Κουτί-περίγραμμα με αυτό το στοιχείο τοποθετημένο μέσα
### toBox() {#toBox--}
```
public final IMathBox toBox()
```


Τοποθετεί αυτό το στοιχείο σε μη-οπτικό κουτί (λογική ομαδοποίηση) που χρησιμοποιείται για να ομαδοποιήσει τα στοιχεία μιας εξίσωσης ή άλλο μαθηματικό κείμενο. Ένα κουτιασμένο αντικείμενο μπορεί (για παράδειγμα) να λειτουργήσει ως εξομοιωτής τελεστή με ή χωρίς σημείο ευθυγράμμισης, να χρησιμεύσει ως σημείο αλλαγής γραμμής ή να ομαδοποιηθεί ώστε να μην επιτρέπεται αλλαγή γραμμής εντός.

--------------------

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


Λαμβάνει τα στοιχεία-παιδιά

**Επιστρέφει:**
com.aspose.slides.IMathElement[] - Πίνακας των [IMathElement](../../com.aspose.slides/imathelement)