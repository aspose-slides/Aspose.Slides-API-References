---
title: IMathNaryOperator
second_title: Riferimento API di Aspose.Slides per Java
description: Specifica un oggetto matematico N-ario, come Somma e Integrale.
type: docs
url: /it/com.aspose.slides/imathnaryoperator/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Specifica un oggetto matematico N-ario, come Somma e Integrale. È composto da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getSubscript()](#getSubscript--) | Specifica un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore |
| [getSuperscript()](#getSuperscript--) | Specifica un argomento di apice che, ad esempio, nel caso di un integrale, imposta il limite superiore |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argomento base

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Specifica un argomento di pedice che, ad esempio, nel caso di un integrale, imposta il limite inferiore

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Specifica un argomento di apice che, ad esempio, nel caso di un integrale, imposta il limite superiore

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)