---
title: Integral
second_title: Αναφορά API Aspose.Sildes για .NET
description: Εκτελεί το ολοκλήρωμα
type: docs
weight: 70
url: /el/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Εκτελεί το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | IMathElement | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | IMathElement | Ανώτερο όριο του ολοκληρώματος |
| limitLocations | MathLimitLocations | τοποθεσία των ορίων |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Δείτε Επίσης

* διεπαφή [IMathNaryOperator](../../imathnaryoperator)
* απαριθμητικό [MathIntegralTypes](../../mathintegraltypes)
* διεπαφή [IMathElement](../../imathelement)
* απαριθμητικό [MathLimitLocations](../../mathlimitlocations)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συγκρότημα [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Εκτελεί το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | IMathElement | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | IMathElement | Ανώτερο όριο του ολοκληρώματος |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Δείτε Επίσης

* διεπαφή [IMathNaryOperator](../../imathnaryoperator)
* απαριθμητικό [MathIntegralTypes](../../mathintegraltypes)
* διεπαφή [IMathElement](../../imathelement)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συγκρότημα [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Εκτελεί το ολοκλήρωμα χωρίς όρια

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Δείτε Επίσης

* διεπαφή [IMathNaryOperator](../../imathnaryoperator)
* απαριθμητικό [MathIntegralTypes](../../mathintegraltypes)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συγκρότημα [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Εκτελεί το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | String | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | String | Ανώτερο όριο του ολοκληρώματος |
| limitLocations | MathLimitLocations | τοποθεσία των ορίων |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Δείτε Επίσης

* διεπαφή [IMathNaryOperator](../../imathnaryoperator)
* απαριθμητικό [MathIntegralTypes](../../mathintegraltypes)
* απαριθμητικό [MathLimitLocations](../../mathlimitlocations)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συγκρότημα [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Εκτελεί το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | String | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | String | Ανώτερο όριο του ολοκληρώματος |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Δείτε Επίσης

* διεπαφή [IMathNaryOperator](../../imathnaryoperator)
* απαριθμητικό [MathIntegralTypes](../../mathintegraltypes)
* κλάση [MathElementBase](../../mathelementbase)
* χώρος ονομάτων [Aspose.Slides.MathText](../../mathelementbase)
* συγκρότημα [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->