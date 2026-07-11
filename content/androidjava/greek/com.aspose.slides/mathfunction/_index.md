---
title: MathFunction
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Καθορίζει μια συνάρτηση ενός ορίσματος.
type: docs
url: /el/com.aspose.slides/mathfunction/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Καθορίζει μια συνάρτηση ενός ορίσματος.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης MathFunction. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης MathFunction. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos |
| [getBase()](#getBase--) | Όρισμα συνάρτησης |
| [getChildren()](#getChildren--) | Λήψη στοιχείων παιδιών |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Ιδιότητες χαρακτήρα ελέγχου |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Όρισμα συνάρτησης

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Επιστρέφει:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Λήψη στοιχείων παιδιών

**Επιστρέφει:**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Ιδιότητες χαρακτήρα ελέγχου

**Επιστρέφει:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps