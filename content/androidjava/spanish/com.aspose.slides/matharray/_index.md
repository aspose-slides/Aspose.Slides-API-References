---
title: MathArray
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Especifica una matriz vertical de ecuaciones o cualquier objeto matemático
type: docs
url: /es/com.aspose.slides/matharray/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Especifica una matriz vertical de ecuaciones o cualquier objeto matemático

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Crea una matriz matemática y coloca el elemento especificado en ella |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crea una matriz matemática y coloca los elementos especificados en ella |
## Métodos

| Método | Descripción |
| --- | --- |
| [getArguments()](#getArguments--) | El conjunto de elementos de la matriz |
| [getBaseJustification()](#getBaseJustification--) | Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Distribución máxima. Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Distribución máxima. Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Distribución de objeto. Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Distribución de objeto. Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz. |
| [getRowSpacingRule()](#getRowSpacingRule--) | El tipo de espaciado vertical entre los elementos de la matriz. Valor predeterminado: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | El tipo de espaciado vertical entre los elementos de la matriz. Valor predeterminado: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está configurado en 3, exactamente en cuyo caso la unidad de medida es puntos, o Multiple, en cuyo caso la unidad es medias líneas. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está configurado en 3, exactamente en cuyo caso la unidad de medida es puntos, o Multiple, en cuyo caso la unidad es medias líneas. |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Crea una matriz matemática y coloca el elemento especificado en ella

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento a colocar en la matriz |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Crea una matriz matemática y coloca los elementos especificados en ella

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementos a colocar en la matriz |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final int getBaseJustification()
```

Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center

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
public final void setBaseJustification(int value)
```

Especifica la alineación de la matriz en relación con el texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center

--------------------

> ```
> Example:
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
public final boolean getMaximumDistribution()
```

Distribución máxima. Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Devuelve:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Distribución máxima. Cuando es verdadero, la matriz se espacia al ancho máximo del elemento contenedor (página, columna, celda, etc.).

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
public final boolean getObjectDistribution()
```

Distribución de objeto. Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Devuelve:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Distribución de objeto. Cuando es verdadero, el contenido de la matriz se espacia al ancho máximo del objeto matriz.

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
public final int getRowSpacingRule()
```

El tipo de espaciado vertical entre los elementos de la matriz. Valor predeterminado: SingleLineGap

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
public final void setRowSpacingRule(int value)
```

El tipo de espaciado vertical entre los elementos de la matriz. Valor predeterminado: SingleLineGap

--------------------

> ```
> Example:
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
public final long getRowSpacing()
```

Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está configurado en 3, exactamente en cuyo caso la unidad de medida es puntos, o Multiple, en cuyo caso la unidad es medias líneas. Valor predeterminado: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Devuelve:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está configurado en 3, exactamente en cuyo caso la unidad de medida es puntos, o Multiple, en cuyo caso la unidad es medias líneas. Valor predeterminado: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtiene los elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]