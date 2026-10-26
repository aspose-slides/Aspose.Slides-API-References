---
title: AsArgumentOfFunction
second_title: Aspose.Sildes για .NET API Αναφορά
description: Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα
type: docs
weight: 20
url: /el/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## AsArgumentOfFunction(IMathElement) {#asargumentoffunction}

Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(IMathElement functionName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | IMathElement | Όνομα συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(functionName);
```

### Δείτε επίσης

* διασύνδεση [IMathFunction](../../imathfunction)
* διασύνδεση [IMathElement](../../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../imathelement)
* συλλογή [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(string) {#asargumentoffunction_4}

Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(string functionName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionName | String | Όνομα συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction("cos");
```

### Δείτε επίσης

* διασύνδεση [IMathFunction](../../imathfunction)
* διασύνδεση [IMathElement](../../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../imathelement)
* συλλογή [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfOneArgument) {#asargumentoffunction_1}

Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfOneArgument | Ένας από τους συνηθισμένους τύπους συναρτήσεων ενός ορίσματος |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
```

### Δείτε επίσης

* διασύνδεση [IMathFunction](../../imathfunction)
* απαρίθμηση [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument)
* διασύνδεση [IMathElement](../../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../imathelement)
* συλλογή [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, IMathElement) {#asargumentoffunction_2}

Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο επιπλέον όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    IMathElement additionalArgument)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Ένας από τους συνηθισμένους τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | IMathElement | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathElement logarithmBase = new MathematicalText("5");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
```

### Δείτε επίσης

* διασύνδεση [IMathFunction](../../imathfunction)
* απαρίθμηση [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* διασύνδεση [IMathElement](../../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../imathelement)
* συλλογή [Aspose.Slides](../../../)

---

## AsArgumentOfFunction(MathFunctionsOfTwoArguments, string) {#asargumentoffunction_3}

Λαμβάνει τη συγκεκριμένη συνάρτηση χρησιμοποιώντας αυτήν την παρουσία ως όρισμα και το καθορισμένο επιπλέον όρισμα

```csharp
public IMathFunction AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, 
    string additionalArgument)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| functionType | MathFunctionsOfTwoArguments | Ένας από τους συνηθισμένους τύπους συναρτήσεων δύο ορισμάτων: Log, Lim, Min, Max |
| additionalArgument | String | Πρόσθετο όρισμα ανάλογα με τον τύπο της συνάρτησης |

### Τιμή επιστροφής

Νέο μαθηματικό στοιχείο τύπου [`IMathFunction`](../../imathfunction)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionArg.AsArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Επιστρέφει το λογάριθμο του 'x' στη βάση '5'
```

### Δείτε επίσης

* διασύνδεση [IMathFunction](../../imathfunction)
* απαρίθμηση [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments)
* διασύνδεση [IMathElement](../../imathelement)
* χώρο ονομάτων [Aspose.Slides.MathText](../../imathelement)
* συλλογή [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->