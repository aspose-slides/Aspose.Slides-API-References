---
title: IColorFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa uma cor usada em uma apresentação.
type: docs
url: /pt/com.aspose.slides/icolorformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Representa uma cor usada em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColorType()](#getColorType--) | Retorna ou define o método de definição de cor. |
| [setColorType(int value)](#setColorType-int-) | Retorna ou define o método de definição de cor. |
| [getColor()](#getColor--) | Retorna a cor resultante (com todas as transformações de cor aplicadas). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Retorna a cor resultante (com todas as transformações de cor aplicadas). |
| [getPresetColor()](#getPresetColor--) | Retorna ou define a cor predefinida. |
| [setPresetColor(int value)](#setPresetColor-int-) | Retorna ou define a cor predefinida. |
| [getSystemColor()](#getSystemColor--) | Retorna ou define a cor identificada pela tabela de cores do sistema. |
| [setSystemColor(int value)](#setSystemColor-int-) | Retorna ou define a cor identificada pela tabela de cores do sistema. |
| [getSchemeColor()](#getSchemeColor--) | Retorna ou define a cor identificada por um esquema de cores. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Retorna ou define a cor identificada por um esquema de cores. |
| [getR()](#getR--) | Retorna ou define o componente vermelho de uma cor. |
| [setR(byte value)](#setR-byte-) | Retorna ou define o componente vermelho de uma cor. |
| [getG()](#getG--) | Retorna ou define o componente verde de uma cor. |
| [setG(byte value)](#setG-byte-) | Retorna ou define o componente verde de uma cor. |
| [getB()](#getB--) | Retorna ou define o componente azul de uma cor. |
| [setB(byte value)](#setB-byte-) | Retorna ou define o componente azul de uma cor. |
| [getFloatR()](#getFloatR--) | Retorna ou define o componente vermelho de uma cor. |
| [setFloatR(float value)](#setFloatR-float-) | Retorna ou define o componente vermelho de uma cor. |
| [getFloatG()](#getFloatG--) | Retorna ou define o componente verde de uma cor. |
| [setFloatG(float value)](#setFloatG-float-) | Retorna ou define o componente verde de uma cor. |
| [getFloatB()](#getFloatB--) | Retorna ou define o componente azul de uma cor. |
| [setFloatB(float value)](#setFloatB-float-) | Retorna ou define o componente azul de uma cor. |
| [getHue()](#getHue--) | Retorna ou define o componente matiz de uma cor na representação HSL. |
| [setHue(float value)](#setHue-float-) | Retorna ou define o componente matiz de uma cor na representação HSL. |
| [getSaturation()](#getSaturation--) | Retorna ou define o componente saturação de uma cor na representação HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Retorna ou define o componente saturação de uma cor na representação HSL. |
| [getLuminance()](#getLuminance--) | Retorna ou define o componente luminância de uma cor na representação HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Retorna ou define o componente luminância de uma cor na representação HSL. |
| [getColorTransform()](#getColorTransform--) | Retorna a coleção de transformações de cor aplicadas a uma cor. |
| [toString(int format)](#toString-int-) | Retorna uma String que representa o formato de cor atual. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copia o formato de cor de "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Retorna ou define o método de definição de cor. Leitura/gravação [ColorType](../../com.aspose.slides/colortype).

**Retorno:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Retorna ou define o método de definição de cor. Leitura/gravação [ColorType](../../com.aspose.slides/colortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura/gravação java.awt.Color.

**Retorno:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura/gravação java.awt.Color.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Retorna ou define a cor predefinida. Leitura/gravação [PresetColor](../../com.aspose.slides/presetcolor).

**Retorno:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Retorna ou define a cor predefinida. Leitura/gravação [PresetColor](../../com.aspose.slides/presetcolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Retorna ou define a cor identificada pela tabela de cores do sistema. Leitura/gravação [SystemColor](../../com.aspose.slides/systemcolor).

**Retorno:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Retorna ou define a cor identificada pela tabela de cores do sistema. Leitura/gravação [SystemColor](../../com.aspose.slides/systemcolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Retorna ou define a cor identificada por um esquema de cores. Leitura/gravação [SchemeColor](../../com.aspose.slides/schemecolor).

**Retorno:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Retorna ou define a cor identificada por um esquema de cores. Leitura/gravação [SchemeColor](../../com.aspose.slides/schemecolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Retorno:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Retorno:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Retorno:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Retorna ou define o componente matiz de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Retorna ou define o componente matiz de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Retorna ou define o componente saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Retorna ou define o componente saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Retorna ou define o componente luminância de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Retorno:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Retorna ou define o componente luminância de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Retorna a coleção de transformações de cor aplicadas a uma cor. Somente leitura [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retorno:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Retorna uma String que representa o formato de cor atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | int | Um tipo de formato de string de cor. |

**Retorno:**
java.lang.String - Uma string que representa o formato de cor atual.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Copie o formato de cor de "color".

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Cor [IColorFormat](../../com.aspose.slides/icolorformat) |