---
title: MathSubscriptElement
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l'objet indice qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite.
type: docs
url: /fr/com.aspose.slides/mathsubscriptelement/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)  
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

Spécifie l'objet indice, qui se compose d'une base et d'un indice de taille réduite placé en dessous et à droite.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathSubscriptElement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSubscript()](#getSubscript--) | Indice |
| [getChildren()](#getChildren--) | Récupère les éléments enfants |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

Initialise une nouvelle instance de la classe MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

Indice

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**Valeur de retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Récupère les éléments enfants

**Valeur de retour:**
com.aspose.slides.IMathElement[]