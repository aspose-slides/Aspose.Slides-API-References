---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Represents a gradient format.
type: docs
url: /pt/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Representa um formato de gradiente.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Returns or sets the position (0..1) of a gradient stop. Read/write float.

**Retorna:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Returns or sets the position (0..1) of a gradient stop. Read/write float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Returns the color of a gradient stop. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)