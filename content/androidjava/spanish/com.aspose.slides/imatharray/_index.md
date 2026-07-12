---
title: IMathArray
second_title: Aspose.Slides para Android a través de la referencia de la API de Java
description: Especifica una matriz vertical de ecuaciones o cualquier objeto matemático
type: docs
url: /es/com.aspose.slides/imatharray/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Especifica una matriz vertical de ecuaciones o cualquier objeto matemático

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getArguments()](#getArguments--) | El conjunto de elementos de la matriz |
| [getBaseJustification()](#getBaseJustification--) | Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribución máxima Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribución máxima Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribución de objeto Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribución de objeto Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz. |
| [getRowSpacingRule()](#getRowSpacingRule--) | El tipo de espaciado vertical entre los elementos de la matriz |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | El tipo de espaciado vertical entre los elementos de la matriz |
| [getRowSpacing()](#getRowSpacing--) | Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida es puntos o Múltiple, en cuyo caso la unidad es medio-líneas. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida es puntos o Múltiple, en cuyo caso la unidad es medio-líneas. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

El conjunto de elementos de la matriz

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Devuelve:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Devuelve:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center

--------------------

> ```
> Ejemplo:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Distribución máxima Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.).

--------------------

> ```
> Ejemplo:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Devuelve:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Distribución máxima Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Distribución de objeto Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz.

--------------------

> ```
> Ejemplo:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Devuelve:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Distribución de objeto Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

El tipo de espaciado vertical entre los elementos de la matriz

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Devuelve:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

El tipo de espaciado vertical entre los elementos de la matriz

--------------------

> ```
> Ejemplo:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida es puntos o Múltiple, en cuyo caso la unidad es medio-líneas. Valor predeterminado: 0

--------------------

> ```
> Ejemplo:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Devuelve:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida es puntos o Múltiple, en cuyo caso la unidad es medio-líneas. Valor predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |