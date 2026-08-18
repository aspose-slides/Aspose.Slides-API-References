---
title: ShapeFrame
second_title: Referência da API Aspose.Slides para Java
description: Representa as propriedades dos quadros de forma.
type: docs
url: /pt/com.aspose.slides/shapeframe/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Representa as propriedades do quadro de forma.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Cria novas propriedades do quadro de forma. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getX()](#getX--) | Retorna a coordenada X do canto superior esquerdo de um quadro. |
| [getY()](#getY--) | Retorna a coordenada Y do canto superior esquerdo de um quadro. |
| [getWidth()](#getWidth--) | Retorna a largura de um quadro. |
| [getHeight()](#getHeight--) | Retorna a altura de um quadro. |
| [getRotation()](#getRotation--) | Retorna o número de graus que um quadro está rotacionado ao redor do eixo z. |
| [getCenterX()](#getCenterX--) | Retorna a coordenada X do centro de um quadro. |
| [getCenterY()](#getCenterY--) | Retorna a coordenada Y do centro de um quadro. |
| [getFlipH()](#getFlipH--) | Determina se um quadro está invertido horizontalmente. |
| [getFlipV()](#getFlipV--) | Determina se um quadro está invertido verticalmente. |
| [getRectangle()](#getRectangle--) | Retorna as coordenadas de um quadro. |
| [deepClone()](#deepClone--) | Clona |
| [cloneT()](#cloneT--) | Clona. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Retorna um valor que indica se esta instância é igual a um objeto especificado. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Retorna um valor que indica se esta instância é igual a um objeto especificado. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Cria novas propriedades do quadro de forma.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | Coordenada X de um quadro. |
| y | float | Coordenada Y de um quadro. |
| width | float | Largura de um quadro. |
| height | float | Altura de um quadro. |
| flipH | byte | Verdadeiro se o quadro estiver invertido horizontalmente. |
| flipV | byte | Verdadeiro se o quadro estiver invertido verticalmente. |
| rotationAngle | float | Número de graus que o quadro está rotacionado. |

### getX() {#getX--}
```
public final float getX()
```

Retorna a coordenada X do canto superior esquerdo de um quadro. Somente leitura float.

**Retorna:**
float
### getY() {#getY--}
```
public final float getY()
```

Retorna a coordenada Y do canto superior esquerdo de um quadro. Somente leitura float.

**Retorna:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retorna a largura de um quadro. Somente leitura float.

**Retorna:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retorna a altura de um quadro. Somente leitura float.

**Retorna:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retorna o número de graus que um quadro está rotacionado ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Somente leitura float.

**Retorna:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Retorna a coordenada X do centro de um quadro. Somente leitura float.

**Retorna:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Retorna a coordenada Y do centro de um quadro. Somente leitura float.

**Retorna:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Determina se um quadro está invertido horizontalmente. Somente leitura [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Determina se um quadro está invertido verticalmente. Somente leitura [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Retorna as coordenadas de um quadro. Somente leitura java.awt.geom.Rectangle2D.Float.

**Retorna:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clona

**Retorna:**
java.lang.Object - Quadro de forma clonado.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Clona.

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Quadro de forma clonado.
### hashCode() {#hashCode--}
```
public int hashCode()
```



**Retorna:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Retorna um valor que indica se esta instância é igual a um objeto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O objeto a ser comparado com esta instância. |

**Retorna:**
boolean - **true** se obj for um ShapeFrame que tem o mesmo valor desta instância; caso contrário, **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Retorna um valor que indica se esta instância é igual a um objeto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | O ShapeFRameEx a ser comparado com esta instância. |

**Retorna:**
boolean - **true** se value for um ShapeFrame que tem o mesmo valor desta instância; caso contrário, **false**.