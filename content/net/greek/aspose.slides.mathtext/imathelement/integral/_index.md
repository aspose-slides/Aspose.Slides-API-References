---
title: Integral
second_title: Aspose.Sildes για .NET Αναφορά API
description: Λαμβάνει το ολοκλήρωμα
type: docs
weight: 80
url: /el/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Λαμβάνει το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | IMathElement | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | IMathElement | Ανώτερο όριο του ολοκληρώματος |
| limitLocations | MathLimitLocations | Τοποθεσία των ορίων |

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

### Δείτε επίσης

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Λαμβάνει το ολοκλήρωμα

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

### Δείτε επίσης

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Λαμβάνει το ολοκλήρωμα χωρίς όρια

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

### Δείτε επίσης

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Λαμβάνει το ολοκλήρωμα

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| integralType | MathIntegralTypes | Τύπος ολοκληρώματος |
| lowerLimit | String | Κατώτερο όριο του ολοκληρώματος |
| upperLimit | String | Ανώτερο όριο του ολοκληρώματος |
| limitLocations | MathLimitLocations | Τοποθεσία των ορίων |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [`IMathNaryOperator`](../../imathnaryoperator)

### Παραδείγματα

Παράδειγμα:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Δείτε επίσης

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Λαμβάνει το ολοκλήρωμα

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

### Δείτε επίσης

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->