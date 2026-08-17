---
title: MathFunction
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie une fonction d'un argument.
type: docs
url: /fr/com.aspose.slides/mathfunction/
---
**Héritage :**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Spécifie une fonction d'un argument.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathFunction. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathFunction. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Nom de fonction. Par exemple, les noms de fonctions sont sin et cos |
| [getBase()](#getBase--) | Argument de fonction |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés de caractères de contrôle |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```

Initialise une nouvelle instance de la classe MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```

Initialise une nouvelle instance de la classe MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```

Nom de fonction. Par exemple, les noms de fonctions sont sin et cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Retour :**  
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de fonction

--------------------

> ```
> Exemple:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Retour :**  
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Retour :**  
com.aspose.slides.IMathElement[] - Tableau de [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés de caractères de contrôle

**Retour :**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps