---
title: AsArgumentOfFunction
second_title: Aspose.Sildes για .NET Αναφορά API
description: Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα
type: docs
weight: 20
url: /el/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Παρέχει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | IMathElement | Όνομα συνάρτησης |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Δείτε επίσης

* διεπαφή [IMathFunction](../../imathfunction)
* διεπαφή [IMathElement](../../imathelement)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Παρέχει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | String | Όνομα συνάρτησης |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Δείτε επίσης

* διεπαφή [IMathFunction](../../imathfunction)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Παρέχει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Ένας από τους κοινά τύπους συναρτήσεων ενός ορίσματος |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Δείτε επίσης

* διεπαφή [IMathFunction](../../imathfunction)
* αρίθμηση [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Παρέχει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Ένας από τους κοινά τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Πρόσθετο όρισμα ανάλογο του τύπου της συνάρτησης |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Επιστρέφει τον λογάριθμο του 'x' στη βάση '5'
```

### Δείτε επίσης

* διεπαφή [IMathFunction](../../imathfunction)
* αρίθμηση [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* διεπαφή [IMathElement](../../imathelement)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συναρμολόγηση [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Παρέχει την καθορισμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο πρόσθετο όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Ένας από τους κοινά τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | String | Πρόσθετο όρισμα ανάλογο του τύπου της συνάρτησης |

### Τιμή Επιστροφής

Νέο στοιχείο μαθηματικών τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Επιστρέφει τον λογάριθμο του 'x' στη βάση '5'
```

### Δείτε επίσης

* διεπαφή [IMathFunction](../../imathfunction)
* αρίθμηση [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συναρμολόγηση [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->