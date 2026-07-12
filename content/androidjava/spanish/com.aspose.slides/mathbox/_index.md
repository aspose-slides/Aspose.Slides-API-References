---
title: MathBox
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Especifica el empaquetado lógico de un elemento matemático.
type: docs
url: /es/com.aspose.slides/mathbox/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Especifica el empaquetado lógico (boxeo) de un elemento matemático. Por ejemplo, un objeto empaquetado puede servir como un emulador de operador con o sin un punto de alineación, servir como un punto de salto de línea, o agruparse de forma que no se permitan saltos de línea dentro. Por ejemplo, el operador "==" debe empaquetarse para evitar saltos de línea.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Inicializa MathBox con el elemento especificado como argumento |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Emulador de Operador. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Emulador de Operador. |
| [getNoBreak()](#getNoBreak--) | Sin salto Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Sin salto Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. |
| [getDifferential()](#getDifferential--) | Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (p.ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (p.ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. |
| [getExplicitBreak()](#getExplicitBreak--) | Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto Box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto Box. |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de Caracteres de Control |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Inicializa MathBox con el elemento especificado como argumento

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica el cuadro. Puede ser nulo. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Emulador de Operador. Cuando es verdadero, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como un punto de salto de línea y puede alinearse con otros operadores. Los Emuladores de Operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Devuelve:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Emulador de Operador. Cuando es verdadero, el cuadro y su contenido se comportan como un único operador y heredan las propiedades de un operador. Esto significa, por ejemplo, que el carácter puede servir como un punto de salto de línea y puede alinearse con otros operadores. Los Emuladores de Operador se usan a menudo cuando uno o más glifos se combinan para formar un operador, como '=='. Valor predeterminado: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

Sin salto Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. Cuando es verdadero, no pueden producirse saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro del cuadro. Predeterminado: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Devuelve:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

Sin salto Esta propiedad especifica la propiedad "unbreakable" en el cuadro del objeto. Cuando es verdadero, no pueden producirse saltos de línea dentro del cuadro. Esto puede ser importante para emuladores de operadores que constan de más de un operador binario. Cuando este elemento no se especifica, pueden producirse saltos dentro del cuadro. Predeterminado: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (p.ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false

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
public final void setDifferential(boolean value)
```

Diferencial Cuando es verdadero, el cuadro actúa como un diferencial (p.ej., \\ud835\\udc51\\ud835\\udc65 en un integrando), y recibe el espaciado horizontal apropiado para el diferencial matemático. Predeterminado: false

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
public final boolean getAlignmentPoint()
```

Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false

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
public final void setAlignmentPoint(boolean value)
```

Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false

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
public final byte getExplicitBreak()
```

Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático. Valores posibles: 1..255 Valor predeterminado: 0 (sin salto explícito)

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
public final void setExplicitBreak(byte value)
```

Salto explícito especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se usará como punto de alineación para la línea actual de texto matemático. Valores posibles: 1..255 Valor predeterminado: 0 (sin salto explícito)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propiedades de Caracteres de Control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps