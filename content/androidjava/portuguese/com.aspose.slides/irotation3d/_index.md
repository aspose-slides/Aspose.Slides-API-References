---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /pt/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Representa a rotação 3D de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRotationX()](#getRotationX--) | Retorna ou define o grau de rotação ao redor do eixo X, ou seja, |
| [setRotationX(byte value)](#setRotationX-byte-) | Retorna ou define o grau de rotação ao redor do eixo X, ou seja, |
| [getRotationY()](#getRotationY--) | Retorna ou define o grau de rotação ao redor do eixo Y, ou seja, |
| [setRotationY(int value)](#setRotationY-int-) | Retorna ou define o grau de rotação ao redor do eixo Y, ou seja, |
| [getPerspective()](#getPerspective--) | Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. |
| [getDepthPercents()](#getDepthPercents--) | Retorna ou define a profundidade de um gráfico 3D como porcentagem da largura do gráfico (entre 20 e 2000 por cento). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Retorna ou define a profundidade de um gráfico 3D como porcentagem da largura do gráfico (entre 20 e 2000 por cento). |
| [getHeightPercents()](#getHeightPercents--) | Especifica a altura de um gráfico 3-D como porcentagem da largura do gráfico (entre 5 e 500 por cento). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Especifica a altura de um gráfico 3-D como porcentagem da largura do gráfico (entre 5 e 500 por cento). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Retorna ou define o grau de rotação ao redor do eixo X, ou seja, na direção Y para gráficos 3D (entre -90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (X Rotation) no ECMA-376 e à opção "Y Rotation" no PowerPoint 2007+. Byte de leitura/gravação.

**Retorna:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Retorna ou define o grau de rotação ao redor do eixo X, ou seja, na direção Y para gráficos 3D (entre -90 e 90 graus). A propriedade corresponde ao item 21.2.2.157 rotX (X Rotation) no ECMA-376 e à opção "Y Rotation" no PowerPoint 2007+. Byte de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Retorna ou define o grau de rotação ao redor do eixo Y, ou seja, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Y Rotation) no ECMA-376 e à opção "X Rotation" no PowerPoint 2007+. Int de leitura/gravação.

**Retorna:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Retorna ou define o grau de rotação ao redor do eixo Y, ou seja, na direção X para gráficos 3D (entre 0 e 360 graus). A propriedade corresponde ao item 21.2.2.158 rotY (Y Rotation) no ECMA-376 e à opção "X Rotation" no PowerPoint 2007+. Int de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). Ignorado se o valor da propriedade RightAngleAxes for true. Byte de leitura/gravação.

**Retorna:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Retorna ou define o valor de perspectiva (ângulo de campo de visão) para gráficos 3D (entre 0 e 100). Ignorado se o valor da propriedade RightAngleAxes for true. Byte de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos do gráfico são independentes da rotação ou elevação do gráfico. Booleano de leitura/gravação.

**Retorna:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Determina se os eixos do gráfico estão em ângulos retos, em vez de desenhados em perspectiva. Em outras palavras, determina se os ângulos dos eixos do gráfico são independentes da rotação ou elevação do gráfico. Booleano de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Retorna ou define a profundidade de um gráfico 3D como porcentagem da largura do gráfico (entre 20 e 2000 por cento). Int de leitura/gravação.

**Retorna:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Retorna ou define a profundidade de um gráfico 3D como porcentagem da largura do gráfico (entre 20 e 2000 por cento). Int de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Especifica a altura de um gráfico 3-D como porcentagem da largura do gráfico (entre 5 e 500 por cento). Int de leitura/gravação.

**Retorna:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Especifica a altura de um gráfico 3-D como porcentagem da largura do gráfico (entre 5 e 500 por cento). Int de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |