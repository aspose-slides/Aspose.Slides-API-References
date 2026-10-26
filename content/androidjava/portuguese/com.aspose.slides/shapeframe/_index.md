---
title: ShapeFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades das molduras de forma.
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

Representa as propriedades da moldura da forma.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Cria novas propriedades da moldura da forma. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getX()](#getX--) | Retorna a coordenada X do canto superior esquerdo de uma moldura. |
| [getY()](#getY--) | Retorna a coordenada Y do canto superior esquerdo de uma moldura. |
| [getWidth()](#getWidth--) | Retorna a largura de uma moldura. |
| [getHeight()](#getHeight--) | Retorna a altura de uma moldura. |
| [getRotation()](#getRotation--) | Retorna o número de graus que uma moldura está rotacionada ao redor do eixo z. |
| [getCenterX()](#getCenterX--) | Retorna a coordenada X do centro de uma moldura. |
| [getCenterY()](#getCenterY--) | Retorna a coordenada Y do centro de uma moldura. |
| [getFlipH()](#getFlipH--) | Determina se a moldura está virada horizontalmente. |
| [getFlipV()](#getFlipV--) | Determina se a moldura está virada verticalmente. |
| [getRectangle()](#getRectangle--) | Retorna as coordenadas de uma moldura. |
| [deepClone()](#deepClone--) | Clona |
| [cloneT()](#cloneT--) | Clona. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Retorna um valor que indica se esta instância é igual a um objeto especificado. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Retorna um valor que indica se esta instância é igual a um objeto especificado. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Cria novas propriedades da moldura da forma.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | float | Coordenada X de uma moldura. |
| y | float | Coordenada Y de uma moldura. |
| width | float | Largura de uma moldura. |
| height | float | Altura de uma moldura. |
| flipH | byte | Verdadeiro se a moldura estiver virada horizontalmente. |
| flipV | byte | Verdadeiro se a moldura estiver virada verticalmente. |
| rotationAngle | float | Número de graus que a moldura está rotacionada. |

### getX() {#getX--}
```
public final float getX()
```

Retorna a coordenada X do canto superior esquerdo de uma moldura. Somente leitura float.

**Retorna:**
float
### getY() {#getY--}
```
public final float getY()
```

Retorna a coordenada Y do canto superior esquerdo de uma moldura. Somente leitura float.

**Retorna:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retorna a largura de uma moldura. Somente leitura float.

**Retorna:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retorna a altura de uma moldura. Somente leitura float.

**Retorna:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retorna o número de graus que uma moldura está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Somente leitura float.

**Retorna:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Retorna a coordenada X do centro de uma moldura. Somente leitura float.

**Retorna:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Retorna a coordenada Y do centro de uma moldura. Somente leitura float.

**Retorna:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Determina se a moldura está virada horizontalmente. Somente leitura [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Determina se a moldura está virada verticalmente. Somente leitura [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```

Retorna as coordenadas de uma moldura. Somente leitura android.graphics.RectF.

**Retorna:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clona

**Retorna:**
java.lang.Object - Cloned shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Clona.

**Retorna:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Cloned shape frame.
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