---
title: IOuterShadow
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito de sombra externa.
type: docs
url: /pt/com.aspose.slides/ioutershadow/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Representa um efeito de sombra externa.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Raio de desfoque, em pontos. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Raio de desfoque, em pontos. |
| [getDirection()](#getDirection--) | Direção da sombra, em graus. |
| [setDirection(float value)](#setDirection-float-) | Direção da sombra, em graus. |
| [getDistance()](#getDistance--) | Distância da sombra ao objeto, em pontos. |
| [setDistance(double value)](#setDistance-double-) | Distância da sombra ao objeto, em pontos. |
| [getShadowColor()](#getShadowColor--) | Cor da sombra. |
| [getRectangleAlign()](#getRectangleAlign--) | Alinhamento do retângulo. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Alinhamento do retângulo. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Ângulo de inclinação horizontal, em graus. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Ângulo de inclinação horizontal, em graus. |
| [getSkewVertical()](#getSkewVertical--) | Ângulo de inclinação vertical, em graus. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Ângulo de inclinação vertical, em graus. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indica se a sombra gira junto com a forma. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indica se a sombra gira junto com a forma. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Fator de escala horizontal, em percentual do tamanho original. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Fator de escala horizontal, em percentual do tamanho original. |
| [getScaleVertical()](#getScaleVertical--) | Fator de escala vertical, em percentual do tamanho original. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Fator de escala vertical, em percentual do tamanho original. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Raio de desfoque, em pontos. Valor padrão - 0 pt. Leitura/Gravação double.

**Retorna:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Raio de desfoque, em pontos. Valor padrão - 0 pt. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direção da sombra, em graus. Valor padrão - 0 � (da esquerda para a direita). Leitura/Gravação float.

**Retorna:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Direção da sombra, em graus. Valor padrão - 0 � (da esquerda para a direita). Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distância da sombra ao objeto, em pontos. Valor padrão - 0 pt. Leitura/Gravação double.

**Retorna:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Distância da sombra ao objeto, em pontos. Valor padrão - 0 pt. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Cor da sombra. Valor padrão - preto automático (dependente do tema). Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Alinhamento do retângulo. Valor padrão - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Leitura/Gravação [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Retorna:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Alinhamento do retângulo. Valor padrão - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Leitura/Gravação [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Ângulo de inclinação horizontal, em graus. Valor padrão - 0 �. Leitura/Gravação double.

**Retorna:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Ângulo de inclinação horizontal, em graus. Valor padrão - 0 �. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Ângulo de inclinação vertical, em graus. Valor padrão - 0 �. Leitura/Gravação double.

**Retorna:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Ângulo de inclinação vertical, em graus. Valor padrão - 0 �. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Indica se a sombra gira junto com a forma. Valor padrão - true. Leitura/Gravação boolean.

**Retorna:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Indica se a sombra gira junto com a forma. Valor padrão - true. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Fator de escala horizontal, em percentual do tamanho original. Escala negativa causa uma inversão. Valor padrão - 100 %. Leitura/Gravação double.

**Retorna:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Fator de escala horizontal, em percentual do tamanho original. Escala negativa causa uma inversão. Valor padrão - 100 %. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Fator de escala vertical, em percentual do tamanho original. Escala negativa causa uma inversão. Valor padrão - 100 %. Leitura/Gravação double.

**Retorna:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Fator de escala vertical, em percentual do tamanho original. Escala negativa causa uma inversão. Valor padrão - 100 %. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |