---
title: MathRadical
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie la fonction radicale composée d'une base et d'un degré optionnel.
type: docs
url: /fr/com.aspose.slides/mathradical/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Spécifie la fonction radicale, composée d'une base et d'un degré optionnel. Exemple d'objet radical : \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathRadical. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getDegree()](#getDegree--) | Argument de degré |
| [getHideDegree()](#getHideDegree--) | Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés de caractère de contrôle |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Initialise une nouvelle instance de la classe MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Degré |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Argument de degré

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Renvoie:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriétés de caractère de contrôle

**Renvoie:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtenir les éléments enfants

**Renvoie:**
com.aspose.slides.IMMathElement[]