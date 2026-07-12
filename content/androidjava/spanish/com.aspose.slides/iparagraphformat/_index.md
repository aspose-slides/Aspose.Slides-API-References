---
title: IParagraphFormat
second_title: Aspose.Slides para Android vía la referencia de API Java
description: Esta clase contiene las propiedades de formato de párrafo.
type: docs
url: /es/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), todas las propiedades de esta clase son modificables.

--------------------

Esta clase se utiliza para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo en particular. Esto significa que no se aplica herencia al obtener valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined". Para obtener los valores de los parámetros de formato efectivos, incluyendo los heredados, debe utilizar el método [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) que devuelve una instancia de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Métodos

| Método | Descripción |
| --- | --- |
| [getBullet()](#getBullet--) | Devuelve el formato de viñeta del párrafo. |
| [getDepth()](#getDepth--) | Devuelve o establece la profundidad del párrafo. |
| [setDepth(short value)](#setDepth-short-) | Devuelve o establece la profundidad del párrafo. |
| [getAlignment()](#getAlignment--) | Devuelve o establece la alineación del texto en un párrafo sin herencia. |
| [setAlignment(int value)](#setAlignment-int-) | Devuelve o establece la alineación del texto en un párrafo sin herencia. |
| [getSpaceWithin()](#getSpaceWithin--) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. |
| [getSpaceAfter()](#getSpaceAfter--) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina si se utiliza el salto de línea asiático oriental en un párrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina si se utiliza el salto de línea asiático oriental en un párrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina si se utiliza el salto de línea latino en un párrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina si se utiliza el salto de línea latino en un párrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina si se utiliza la puntuación colgante en un párrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina si se utiliza la puntuación colgante en un párrafo. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve o establece el margen izquierdo en un párrafo sin herencia. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Devuelve o establece el margen izquierdo en un párrafo sin herencia. |
| [getMarginRight()](#getMarginRight--) | Devuelve o establece el margen derecho en un párrafo sin herencia. |
| [setMarginRight(float value)](#setMarginRight-float-) | Devuelve o establece el margen derecho en un párrafo sin herencia. |
| [getIndent()](#getIndent--) | Devuelve o establece la sangría de primera línea / sangría colgante del párrafo sin herencia. |
| [setIndent(float value)](#setIndent-float-) | Devuelve o establece la sangría de primera línea / sangría colgante del párrafo sin herencia. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Devuelve o establece el tamaño de tabulación predeterminado sin herencia. |
| [getTabs()](#getTabs--) | Devuelve las tabulaciones de un párrafo. |
| [getFontAlignment()](#getFontAlignment--) | Devuelve o establece la alineación de fuente en un párrafo sin herencia. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Devuelve o establece la alineación de fuente en un párrafo sin herencia. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Devuelve el formato de porción predeterminado de un párrafo. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Devuelve el formato de viñeta del párrafo. Solo lectura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Devuelve:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Devuelve o establece la profundidad del párrafo. El valor 0 significa valor indefinido. Lectura/escritura short.

**Devuelve:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Devuelve o establece la profundidad del párrafo. El valor 0 significa valor indefinido. Lectura/escritura short.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [TextAlignment](../../com.aspose.slides/textalignment).

**Devuelve:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Devuelve o establece la alineación del texto en un párrafo sin herencia. Lectura/escritura [TextAlignment](../../com.aspose.slides/textalignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura float.

**Devuelve:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Devuelve o establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo significa porcentaje, negativo - tamaño en puntos. No se aplica herencia. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio blanco. Un valor negativo especifica el tamaño del espacio blanco en puntos. Lectura/escritura float.

**Devuelve:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Devuelve o establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio blanco. Un valor negativo especifica el tamaño del espacio blanco en puntos. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio blanco. Un valor negativo especifica el tamaño del espacio blanco en puntos. Lectura/escritura float.

**Devuelve:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Devuelve o establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe ocupar el espacio blanco. Un valor negativo especifica el tamaño del espacio blanco en puntos. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Determina si se utiliza el salto de línea asiático oriental en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Determina si se utiliza el salto de línea asiático oriental en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Determina si se utiliza el salto de línea latino en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Devuelve:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Determina si se utiliza la puntuación colgante en un párrafo. No se aplica herencia. Lectura/escritura [NullableBool](../../com.aspose.slides/nullablebool).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura float.

**Devuelve:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Devuelve o establece el margen izquierdo en un párrafo sin herencia. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura float.

**Devuelve:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Devuelve o establece el margen derecho en un párrafo sin herencia. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Devuelve o establece la sangría de primera línea / sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura float.

**Devuelve:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Devuelve o establece la sangría de primera línea / sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura float.

**Devuelve:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Devuelve o establece el tamaño de tabulación predeterminado sin herencia. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [ITabCollection](../../com.aspose.slides/itabcollection).

**Devuelve:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Devuelve o establece la alineación de fuente en un párrafo sin herencia. Lectura/escritura [FontAlignment](../../com.aspose.slides/fontalignment).

**Devuelve:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Devuelve o establece la alineación de fuente en un párrafo sin herencia. Lectura/escritura [FontAlignment](../../com.aspose.slides/fontalignment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia. Solo lectura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Obtiene los datos de formato de párrafo efectos con la herencia aplicada.

**Devuelve:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).