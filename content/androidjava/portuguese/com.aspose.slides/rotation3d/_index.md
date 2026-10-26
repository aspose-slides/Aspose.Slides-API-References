---
title: Rotation3D
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa a rotação 3D de um gráfico.
type: docs
url: /pt/com.aspose.slides/rotation3d/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Representa a rotação 3D de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRotationX()](#getRotationX--) | Retorna ou define o grau de rotação ao redor do eixo X, ou seja |
| [setRotationX(byte value)](#setRotationX-byte-) | Retorna ou define o grau de rotação ao redor do eixo X, ou seja |
| [getRotationY()](#getRotationY--) | Retorna ou define o grau de rotação ao redor do eixo Y, ou seja |
| [setRotationY(int value)](#setRotationY-int-) | Retorna ou define o grau de rotação ao redor do eixo Y, ou seja |
| [getPerspective()](#getPerspective--) | Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. |
| [getDepthPercents()](#getDepthPercents--) | Retorna ou define a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Retorna ou define a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). |
| [getHeightPercents()](#getHeightPercents--) | Especifica a altura de um gráfico 3-D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Especifica a altura de um gráfico 3-D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

Retorna ou define o grau de rotação ao redor do eixo X, isto é, na direção Y para gráficos 3D (entre –90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (X Rotation) na ECMA-376 e à opção “Y Rotation” no PowerPoint 2007+. Leitura/gravação byte.

**Retorna:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

Retorna ou define o grau de rotação ao redor do eixo X, isto é, na direção Y para gráficos 3D (entre –90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (X Rotation) na ECMA-376 e à opção “Y Rotation” no PowerPoint 2007+. Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Retorna ou define o grau de rotação ao redor do eixo Y, isto é, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Y Rotation) na ECMA-376 e à opção “X Rotation” no PowerPoint 2007+. Leitura/gravação int.

**Retorna:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Retorna ou define o grau de rotação ao redor do eixo Y, isto é, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Y Rotation) na ECMA-376 e à opção “X Rotation” no PowerPoint 2007+. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 240). Ignorado se a propriedade RightAngleAxes for true. Leitura/gravação byte.

**Retorna:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 240). Ignorado se a propriedade RightAngleAxes for true. Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos são independentes da rotação ou elevação do gráfico. Leitura/gravação boolean.

**Retorna:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos são independentes da rotação ou elevação do gráfico. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

Retorna ou define a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). Leitura/gravação int.

**Retorna:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

Retorna ou define a profundidade de um gráfico 3D como uma porcentagem da largura do gráfico (entre 20 e 2000 por cento). Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

Especifica a altura de um gráfico 3-D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). Leitura/gravação int.

**Retorna:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

Especifica a altura de um gráfico 3-D como uma porcentagem da largura do gráfico (entre 5 e 500 por cento). Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject