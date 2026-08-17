---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Representa um guia de desenho ajustável.
type: docs
url: /pt/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Representa um guia de desenho ajustável.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOrientation()](#getOrientation--) | Retorna ou define a orientação do guia de desenho. |
| [setOrientation(byte value)](#setOrientation-byte-) | Retorna ou define a orientação do guia de desenho. |
| [getPosition()](#getPosition--) | Retorna ou define a posição do guia de desenho em pontos a partir do canto superior esquerdo do slide. |
| [setPosition(float value)](#setPosition-float-) | Retorna ou define a posição do guia de desenho em pontos a partir do canto superior esquerdo do slide. |
| [getColor()](#getColor--) | Retorna ou define a cor do guia de desenho. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Retorna ou define a cor do guia de desenho. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

Retorna ou define a orientação do guia de desenho. Read/write [Orientation](../../com.aspose.slides/orientation).

**Retorna:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

Retorna ou define a orientação do guia de desenho. Read/write [Orientation](../../com.aspose.slides/orientation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Retorna ou define a posição do guia de desenho em pontos a partir do canto superior esquerdo do slide. Read/write float.

--------------------

O intervalo típico de valores vai de zero até a altura do slide para um guia horizontal e de zero até a largura do slide para um guia vertical.

**Retorna:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Retorna ou define a posição do guia de desenho em pontos a partir do canto superior esquerdo do slide. Read/write float.

--------------------

O intervalo típico de valores vai de zero até a altura do slide para um guia horizontal e de zero até a largura do slide para um guia vertical.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Retorna ou define a cor do guia de desenho. Read/write java.awt.Color.

**Retorna:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Retorna ou define a cor do guia de desenho. Read/write java.awt.Color.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Color |  |