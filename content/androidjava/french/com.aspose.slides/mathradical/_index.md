---
title: MathRadical
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Spécifie la fonction radicale constituée d'une base et d'un degré optionnel.
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

Spécifie la fonction radicale, composée d’une base et d’un degré optionnel. Exemple d’objet radical : \\u221a\\ud835\\udc65.

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initializes a new instance of the MathRadical class. |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getDegree()](#getDegree--) | Degree argument |
| [getHideDegree()](#getHideDegree--) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree When is true, the degree is not shown, as in \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

Initializes a new instance of the MathRadical class.

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Degree |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de base

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```

Argument de degré

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Retourne:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```

Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Retourne:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```

Masquer le degré. Lorsque vrai, le degré n'est pas affiché, comme dans \\u221a\\ud835\\udc65

--------------------

> ```
> Exemple:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
>  ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés du caractère de contrôle

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()

Obtenir les éléments enfants

**Retourne:**
com.aspose.slides.IMathElement[]