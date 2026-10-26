---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Representa propriedades de formatação para elementos de texto de gráfico.
type: docs
url: /pt/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Representa propriedades de formatação para elementos de texto de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Retorna ou define o texto de ancoragem vertical em um TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Retorna ou define o texto de ancoragem vertical em um TextFrame. |
| [getCenterText()](#getCenterText--) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. |
| [setCenterText(byte value)](#setCenterText-byte-) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. |
| [getTextVerticalType()](#getTextVerticalType--) | Determina a orientação do texto. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determina a orientação do texto. |
| [getMarginLeft()](#getMarginLeft--) | Retorna ou define a margem esquerda (pontos) em um TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retorna ou define a margem esquerda (pontos) em um TextFrame. |
| [getMarginRight()](#getMarginRight--) | Retorna ou define a margem direita (pontos) em um TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retorna ou define a margem direita (pontos) em um TextFrame. |
| [getMarginTop()](#getMarginTop--) | Retorna ou define a margem superior (pontos) em um TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retorna ou define a margem superior (pontos) em um TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Retorna ou define a margem inferior (pontos) em um TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retorna ou define a margem inferior (pontos) em um TextFrame. |
| [getWrapText()](#getWrapText--) | True se o texto for ajustado nas margens do TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True se o texto for ajustado nas margens do TextFrame. |
| [getAutofitType()](#getAutofitType--) | Retorna ou define o modo de ajuste automático do texto. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Retorna ou define o modo de ajuste automático do texto. |
| [getRotationAngle()](#getRotationAngle--) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Retorna ou define o texto de ancoragem vertical em um TextFrame. Leitura/Escrita [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retorna:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Retorna ou define o texto de ancoragem vertical em um TextFrame. Leitura/Escrita [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. Leitura/Escrita [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa. Leitura/Escrita [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leitura/Escrita [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retorna:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leitura/Escrita [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Retorna ou define a margem esquerda (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Retorna:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Retorna ou define a margem esquerda (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Retorna ou define a margem direita (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Retorna:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Retorna ou define a margem direita (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Retorna ou define a margem superior (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Retorna:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Retorna ou define a margem superior (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Retorna ou define a margem inferior (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Retorna:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Retorna ou define a margem inferior (pontos) em um TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True se o texto for ajustado nas margens do TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2007/2013). Leitura/Escrita [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True se o texto for ajustado nas margens do TextFrame. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2007/2013). Leitura/Escrita [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Retorna ou define o modo de ajuste automático do texto. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retorna:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Retorna ou define o modo de ajuste automático do texto. A alteração desta propriedade pode produzir certa influência apenas para estas partes do gráfico: DataLabel e DataLabelFormat (suporte total no PowerPoint 2013; no PowerPoint 2007 não há efeito na renderização). Leitura/Escrita [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isso é aplicado independentemente da forma. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leitura/Escrita float.

--------------------

> ```
> Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. 
>  Além disso, o próprio corpo de texto tem uma rotação de -90 graus no sentido anti-horário aplicada a ele. 
>  Então a forma resultante parecerá estar
>  rotacionada, mas o texto dentro dela parecerá como se não tivesse sido rotacionado de forma alguma.
> ```


**Retorna:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não for especificado, a rotação da forma associada é usada. Se for especificado, então isso é aplicado independentemente da forma. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leitura/Escrita float.

--------------------

> ```
> Considere o caso em que uma forma tem uma rotação de 90 graus no sentido horário aplicada a ela. 
>  Além disso, o próprio corpo de texto tem uma rotação de -90 graus 
>  no sentido anti-horário aplicada a ele. Então a forma resultante parecerá
>  estar rotacionada, mas o texto dentro dela parecerá como se não tivesse sido rotacionado de forma alguma.
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |