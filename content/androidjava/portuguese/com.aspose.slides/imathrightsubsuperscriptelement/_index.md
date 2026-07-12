---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto Sub-Superscript que consiste em uma base e um subscrito e sobrescrito posicionados à direita da base.
type: docs
url: /pt/com.aspose.slides/imathrightsubsuperscriptelement/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Especifica o objeto Sub-Superscript, que consiste em uma base e um subscrito e um sobrescrito posicionados à direita da base.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento da base |
| [getSubscript()](#getSubscript--) | Argumento de subscrito |
| [getSuperscript()](#getSuperscript--) | Argumento de sobrescrito |
| [getAlignScripts()](#getAlignScripts--) | Especifica o alinhamento de subscrito/sobrescrito. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Especifica o alinhamento de subscrito/sobrescrito. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento da base

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Argumento de subscrito

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Argumento de sobrescrito

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

Especifica o alinhamento de subscrito/sobrescrito. Quando verdadeiro, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando falso, eles são ajustados à forma da base. O valor padrão é falso.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Retorna:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

Especifica o alinhamento de subscrito/sobrescrito. Quando verdadeiro, subscrito e sobrescrito são alinhados horizontalmente entre si. Quando falso, eles são ajustados à forma da base. O valor padrão é falso.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |