---
title: IColorFormat
second_title: Aspose.Slides para Android via Referência da API Java
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
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Retorna a cor resultante (com todas as transformações de cor aplicadas). |
| [getPresetColor()](#getPresetColor--) | Retorna ou define a predefinição de cor. |
| [setPresetColor(int value)](#setPresetColor-int-) | Retorna ou define a predefinição de cor. |
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
| [getHue()](#getHue--) | Retorna ou define o componente de matiz de uma cor na representação HSL. |
| [setHue(float value)](#setHue-float-) | Retorna ou define o componente de matiz de uma cor na representação HSL. |
| [getSaturation()](#getSaturation--) | Retorna ou define o componente de saturação de uma cor na representação HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Retorna ou define o componente de saturação de uma cor na representação HSL. |
| [getLuminance()](#getLuminance--) | Retorna ou define o componente de luminosidade de uma cor na representação HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Retorna ou define o componente de luminosidade de uma cor na representação HSL. |
| [getColorTransform()](#getColorTransform--) | Retorna a coleção de transformações de cor aplicadas a uma cor. |
| [toString(int format)](#toString-int-) | Retorna uma String que representa o formato de cor atual. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copia o formato de cor de "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Retorna ou define o método de definição de cor. Leitura/Gravação [ColorType](../../com.aspose.slides/colortype).

**Retorna:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Retorna ou define o método de definição de cor. Leitura/Gravação [ColorType](../../com.aspose.slides/colortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura/Gravação java.lang.Integer.

**Retorna:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Retorna a cor resultante (com todas as transformações de cor aplicadas). Define cores RGB e limpa todas as transformações de cor. Leitura/Gravação java.lang.Integer.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Retorna ou define a predefinição de cor. Leitura/Gravação [PresetColor](../../com.aspose.slides/presetcolor).

**Retorna:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Retorna ou define a predefinição de cor. Leitura/Gravação [PresetColor](../../com.aspose.slides/presetcolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Retorna ou define a cor identificada pela tabela de cores do sistema. Leitura/Gravação [SystemColor](../../com.aspose.slides/systemcolor).

**Retorna:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Retorna ou define a cor identificada pela tabela de cores do sistema. Leitura/Gravação [SystemColor](../../com.aspose.slides/systemcolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Retorna ou define a cor identificada por um esquema de cores. Leitura/Gravação [SchemeColor](../../com.aspose.slides/schemecolor).

**Retorna:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Retorna ou define a cor identificada por um esquema de cores. Leitura/Gravação [SchemeColor](../../com.aspose.slides/schemecolor).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Retorna:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Retorna:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Retorna:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Retorna ou define o componente vermelho de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Retorna ou define o componente verde de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Retorna ou define o componente azul de uma cor. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Retorna ou define o componente de matiz de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Retorna ou define o componente de matiz de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Retorna ou define o componente de saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Retorna ou define o componente de saturação de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Retorna ou define o componente de luminosidade de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Retorna:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Retorna ou define o componente de luminosidade de uma cor na representação HSL. Todas as transformações de cor são ignoradas. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Retorna a coleção de transformações de cor aplicadas a uma cor. Somente leitura [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retorna:**
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

**Retorna:**
java.lang.String - Uma string que representa o formato de cor atual.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Copia o formato de cor de "color".

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |