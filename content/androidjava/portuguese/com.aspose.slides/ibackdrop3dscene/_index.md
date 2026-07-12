---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /pt/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Define um plano no qual efeitos, como brilho e sombra, são aplicados em relação à forma à qual são aplicados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Retorna ou define um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Retorna ou define um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Retorna ou define um ponto no espaço 3D. Este ponto é o ponto no espaço que ancora o plano de fundo. Ponto 3D representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Retorna ou define um ponto no espaço 3D. Este ponto é o ponto no espaço que ancora o plano de fundo. Ponto 3D representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Retorna ou define um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Retorna ou define um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |