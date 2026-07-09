---
title: MathBox
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Spécifie l'encapsulation logique (mise en boîte) d'un élément mathématique.
type: docs
url: /fr/com.aspose.slides/mathbox/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Spécifie l’encapsulation logique (mise en boîte) d’un élément mathématique. Par exemple, un objet mis en boîte peut servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de saut de ligne, ou être groupé de façon à ne pas autoriser de sauts de ligne à l’intérieur. Par exemple, l’opérateur "==" doit être mis en boîte pour empêcher les sauts de ligne.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initializes MathBox with the specified element as an argument |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break This property specifies the "unbreakable" property on the object box. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break This property specifies the "unbreakable" property on the object box. |
| [getDifferential()](#getDifferential--) | Differential When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Initializes MathBox with the specified element as an argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base element to which the box is applied. Can be null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Returns:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Pas de rupture Cette propriété spécifie la propriété "incassable" de la boîte d'objet. Lorsque true, aucune rupture de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Exemple :
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Renvoie :**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Pas de rupture Cette propriété spécifie la propriété "incassable" de la boîte d'objet. Lorsque true, aucune rupture de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateurs qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Exemple :
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differential When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Returns:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differential When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Returns:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Returns:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()

Propriétés du caractère de contrôle

**Renvoie:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps