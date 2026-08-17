---
title: IMathNaryOperator
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un objet mathématique n-aire, tel que Somme et Intégrale.
type: docs
url: /fr/com.aspose.slides/imathnaryoperator/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Spécifie un objet mathématique n-aire, tel que Somme et Intégrale. Il se compose d’un opérateur, d’une base (ou opérande), et de limites supérieures et inférieures optionnelles. Des exemples d’opérateurs n-aires sont : Somme, Union, Intersection, Intégrale

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getSubscript()](#getSubscript--) | Spécifie un argument de subscript qui, par exemple, dans le cas d’une intégrale, définit la limite inférieure |
| [getSuperscript()](#getSuperscript--) | Spécifie un argument de supersript qui, par exemple, dans le cas d’une intégrale, définit la limite supérieure |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Spécifie un argument de subscript qui, par exemple, dans le cas d’une intégrale, définit la limite inférieure

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Spécifie un argument de supersript qui, par exemple, dans le cas d’une intégrale, définit la limite supérieure

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)