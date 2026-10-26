---
title: IMathBox
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Especifica el empaquetado lógico (boxing) de un elemento matemático.
type: docs
url: /es/com.aspose.slides/imathbox/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Especifica el empaquetado lógico (boxing) de un elemento matemático. Por ejemplo, un objeto en caja puede servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o agruparse de manera que no se permitan saltos de línea dentro de él. Por ejemplo, el operador "==" debe estar en caja para evitar saltos de línea.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulador de operador. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulador de operador. |
| [getNoBreak()](#getNoBreak--) | Sin salto. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Sin salto. |
| [getDifferential()](#getDifferential--) | Diferencial. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferencial. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Cuando es verdadero, este emulador de operador actúa como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Cuando es verdadero, este emulador de operador actúa como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. |
| [getExplicitBreak()](#getExplicitBreak--) | El salto explícito indica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se envuelve al inicio del objeto caja. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | El salto explícito indica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se envuelve al inicio del objeto caja. |
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


Emulador de operador. Cuando es verdadero, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan frecuentemente cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

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


Emulador de operador. Cuando es verdadero, la caja y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como punto para un salto de línea y puede alinearse con otros operadores. Los emuladores de operador se usan frecuentemente cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

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


Sin salto. Esta propiedad especifica la característica "inhaltable" del objeto caja. Cuando es verdadero, no pueden producirse saltos de línea dentro de la caja. Esto puede ser importante para emuladores de operador que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro de la caja. Predeterminado: true

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


Sin salto. Esta propiedad especifica la característica "inhaltable" del objeto caja. Cuando es verdadero, no pueden producirse saltos de línea dentro de la caja. Esto puede ser importante para emuladores de operador que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro de la caja. Predeterminado: true

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


Diferencial. Cuando es verdadero, la caja actúa como un diferencial (p. ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Valor predeterminado: false

--------------------

> ```
> Example:
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


Diferencial. Cuando es verdadero, la caja actúa como un diferencial (p. ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Valor predeterminado: false

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


Cuando es verdadero, este emulador de operador actúa como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Valor predeterminado: false

--------------------

> ```
> Example:
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


Cuando es verdadero, este emulador de operador actúa como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Valor predeterminado: false

--------------------

> ```
> Example:
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


El salto explícito indica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se envuelve al inicio del objeto caja. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático; valores posibles: 1..255. Predeterminado: 0 (sin salto explícito)

--------------------

> ```
> Example:
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


El salto explícito indica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se envuelve al inicio del objeto caja. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático; valores posibles: 1..255. Predeterminado: 0 (sin salto explícito)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |