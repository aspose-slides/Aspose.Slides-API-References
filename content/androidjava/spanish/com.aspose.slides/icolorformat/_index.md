---
title: IColorFormat
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa un color utilizado en una presentación.
type: docs
url: /es/com.aspose.slides/icolorformat/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Representa un color utilizado en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorType()](#getColorType--) | Devuelve o establece el método de definición del color. |
| [setColorType(int value)](#setColorType-int-) | Devuelve o establece el método de definición del color. |
| [getColor()](#getColor--) | Devuelve el color resultante (con todas las transformaciones de color aplicadas). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Devuelve el color resultante (con todas las transformaciones de color aplicadas). |
| [getPresetColor()](#getPresetColor--) | Devuelve o establece el color predefinido. |
| [setPresetColor(int value)](#setPresetColor-int-) | Devuelve o establece el color predefinido. |
| [getSystemColor()](#getSystemColor--) | Devuelve o establece el color identificado por la tabla de colores del sistema. |
| [setSystemColor(int value)](#setSystemColor-int-) | Devuelve o establece el color identificado por la tabla de colores del sistema. |
| [getSchemeColor()](#getSchemeColor--) | Devuelve o establece el color identificado por un esquema de color. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Devuelve o establece el color identificado por un esquema de color. |
| [getR()](#getR--) | Devuelve o establece el componente rojo de un color. |
| [setR(byte value)](#setR-byte-) | Devuelve o establece el componente rojo de un color. |
| [getG()](#getG--) | Devuelve o establece el componente verde de un color. |
| [setG(byte value)](#setG-byte-) | Devuelve o establece el componente verde de un color. |
| [getB()](#getB--) | Devuelve o establece el componente azul de un color. |
| [setB(byte value)](#setB-byte-) | Devuelve o establece el componente azul de un color. |
| [getFloatR()](#getFloatR--) | Devuelve o establece el componente rojo de un color. |
| [setFloatR(float value)](#setFloatR-float-) | Devuelve o establece el componente rojo de un color. |
| [getFloatG()](#getFloatG--) | Devuelve o establece el componente verde de un color. |
| [setFloatG(float value)](#setFloatG-float-) | Devuelve o establece el componente verde de un color. |
| [getFloatB()](#getFloatB--) | Devuelve o establece el componente azul de un color. |
| [setFloatB(float value)](#setFloatB-float-) | Devuelve o establece el componente azul de un color. |
| [getHue()](#getHue--) | Devuelve o establece el componente tono de un color en representación HSL. |
| [setHue(float value)](#setHue-float-) | Devuelve o establece el componente tono de un color en representación HSL. |
| [getSaturation()](#getSaturation--) | Devuelve o establece el componente de saturación de un color en representación HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Devuelve o establece el componente de saturación de un color en representación HSL. |
| [getLuminance()](#getLuminance--) | Devuelve o establece el componente de luminancia de un color en representación HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Devuelve o establece el componente de luminancia de un color en representación HSL. |
| [getColorTransform()](#getColorTransform--) | Devuelve la colección de transformaciones de color aplicadas a un color. |
| [toString(int format)](#toString-int-) | Devuelve una cadena que representa el formato de color actual. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copiar formato de color de "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Devuelve o establece el método de definición del color. Lectura/escritura [ColorType](../../com.aspose.slides/colortype).

**Devuelve:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Devuelve o establece el método de definición del color. Lectura/escritura [ColorType](../../com.aspose.slides/colortype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Devuelve el color resultante (con todas las transformaciones de color aplicadas). Establece colores RGB y elimina todas las transformaciones de color. Lectura/escritura java.lang.Integer.

**Devuelve:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Devuelve el color resultante (con todas las transformaciones de color aplicadas). Establece colores RGB y elimina todas las transformaciones de color. Lectura/escritura java.lang.Integer.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Devuelve o establece el color predefinido. Lectura/escritura [PresetColor](../../com.aspose.slides/presetcolor).

**Devuelve:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Devuelve o establece el color predefinido. Lectura/escritura [PresetColor](../../com.aspose.slides/presetcolor).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Devuelve o establece el color identificado por la tabla de colores del sistema. Lectura/escritura [SystemColor](../../com.aspose.slides/systemcolor).

**Devuelve:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Devuelve o establece el color identificado por la tabla de colores del sistema. Lectura/escritura [SystemColor](../../com.aspose.slides/systemcolor).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Devuelve o establece el color identificado por un esquema de color. Lectura/escritura [SchemeColor](../../com.aspose.slides/schemecolor).

**Devuelve:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Devuelve o establece el color identificado por un esquema de color. Lectura/escritura [SchemeColor](../../com.aspose.slides/schemecolor).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Devuelve o establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Devuelve:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Devuelve o establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Devuelve o establece el componente verde de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Devuelve:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Devuelve o establece el componente verde de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Devuelve o establece el componente azul de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Devuelve:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Devuelve o establece el componente azul de un color. Todas las transformaciones de color se ignoran. Lectura/escritura byte.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Devuelve o establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Devuelve o establece el componente rojo de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Devuelve o establece el componente verde de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Devuelve o establece el componente verde de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Devuelve o establece el componente azul de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Devuelve o establece el componente azul de un color. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Devuelve o establece el componente tono de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Devuelve o establece el componente tono de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Devuelve o establece el componente de saturación de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Devuelve o establece el componente de saturación de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Devuelve o establece el componente de luminancia de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Devuelve:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Devuelve o establece el componente de luminancia de un color en representación HSL. Todas las transformaciones de color se ignoran. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Devuelve la colección de transformaciones de color aplicadas a un color. Solo lectura [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Devuelve:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Devuelve una cadena que representa el formato de color actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | int | Un tipo de formato de cadena de color. |

**Devuelve:**
java.lang.String - Una cadena que representa el formato de color actual.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Copiar formato de color de "color".

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |