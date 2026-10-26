---
title: Backdrop3DScene
second_title: Aspose.Slides para Android via Referência da API Java
description: Define um plano no qual efeitos, como brilho e sombra, são aplicados em relação à forma à qual são aplicados.
type: docs
url: /pt/com.aspose.slides/backdrop3dscene/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Define um plano no qual efeitos, como brilho e sombra, são aplicados em relação à forma à qual são aplicados.

## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Retorna ou define um vetor normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Retorna ou define um vetor normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Retorna ou define um ponto em espaço 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Retorna ou define um ponto em espaço 3D. |
| [getUpVector()](#getUpVector--) | Retorna ou define um vetor que representa a direção para cima. |
| [setUpVector(float[] value)](#setUpVector-float---) | Retorna ou define um vetor que representa a direção para cima. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Long somente leitura.

**Retorna:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Retorna ou define um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Retorna ou define um vetor normal. Para ser mais preciso, este atributo define um vetor normal à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Retorna ou define um ponto em espaço 3D. Este ponto é o ponto no espaço que ancora o plano de fundo. Ponto 3D representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Retorna ou define um ponto em espaço 3D. Este ponto é o ponto no espaço que ancora o plano de fundo. Ponto 3D representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Retorna ou define um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Retorna:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Retorna ou define um vetor que representa a direção para cima. Para ser mais preciso, este atributo define um vetor que representa a direção para cima em relação à face do plano de fundo. Vetor representado por um array de 3 valores float que definem as coordenadas X, Y e Z. Leitura/gravação float[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float[] |  |