---
title: IMathBox
second_title: Referencia de la API de Aspose.Slides para Java
description: Especifica el empaquetado lógico del elemento matemático.
type: docs
url: /es/com.aspose.slides/imathbox/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Especifica el empaquetado lógico (encapsulamiento) de un elemento matemático. Por ejemplo, un objeto encapsulado puede servir como un emulador de operador con o sin un punto de alineación, servir como punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro. Por ejemplo, el operador "==" debe estar encapsulado para evitar saltos de línea.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Emulador de operador. Cuando es verdadero, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto de salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Devuelve:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Emulador de operador. Cuando es verdadero, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto de salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Sin salto. Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. Cuando es verdadero, no pueden ocurrir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operador que constan de más de un operador binario. Cuando este elemento no está especificado, pueden ocurrir saltos dentro del cuadro. Valor predeterminado: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Devuelve:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Sin salto. Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. Cuando es verdadero, no pueden ocurrir saltos de línea dentro del cuadro. Esto puede ser importante para los emuladores de operador que constan de más de un operador binario. Cuando este elemento no está especificado, pueden ocurrir saltos dentro del cuadro. Valor predeterminado: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Diferencial. Cuando es verdadero, el cuadro actúa como un diferencial (p. ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Valor predeterminado: false

--------------------

> ```
> Ejemplo:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Devuelve:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Diferencial. Cuando es verdadero, el cuadro actúa como un diferencial (p. ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Valor predeterminado: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Valor predeterminado: false

--------------------

> ```
> Ejemplo:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Devuelve:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Valor predeterminado: false

--------------------

> ```
> Ejemplo:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelve al comienzo del objeto. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático; valores posibles: 1..255. Valor predeterminado: 0 (sin salto explícito)

--------------------

> ```
> Ejemplo:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Devuelve:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelve al comienzo del objeto. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático; valores posibles: 1..255. Valor predeterminado: 0 (sin salto explícito)

--------------------

> ```
> Ejemplo:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |