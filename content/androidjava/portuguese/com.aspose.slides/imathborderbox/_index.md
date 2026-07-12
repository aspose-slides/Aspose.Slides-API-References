---
title: IMathBorderBox
second_title: Aspose.Slides para Android via Referência da API Java
description: Desenha um contorno retangular ou outro ao redor do IMathElement.
type: docs
url: /pt/com.aspose.slides/imathborderbox/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Desenha um contorno retangular ou outro ao redor do IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Métodos

| MéTODO | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getHideTop()](#getHideTop--) | Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou visível da borda superior da caixa de contorno. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou visível da borda superior da caixa de contorno. |
| [getHideBottom()](#getHideBottom--) | Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de contorno. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de contorno. |
| [getHideLeft()](#getHideLeft--) | Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou visível da borda esquerda da caixa de contorno. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou visível da borda esquerda da caixa de contorno. |
| [getHideRight()](#getHideRight--) | Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou visível da borda direita da caixa de contorno. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou visível da borda direita da caixa de contorno. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Traço Horizontal (padrão é false) - especifica o estado oculto ou visível de uma linha horizontal riscada. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Traço Horizontal (padrão é false) - especifica o estado oculto ou visível de uma linha horizontal riscada. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Traço Vertical (padrão é false) - especifica o estado oculto ou visível de uma linha vertical riscada. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Traço Vertical (padrão é false) - especifica o estado oculto ou visível de uma linha vertical riscada. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Traço Diagonal Inferior-Esquerda para Superior-Direita (padrão é false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Traço Diagonal Inferior-Esquerda para Superior-Direita (padrão é false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Traço Diagonal Superior-Esquerda para Inferior-Direita (padrão é false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Traço Diagonal Superior-Esquerda para Inferior-Direita (padrão é false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou visível da borda superior da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Retorna:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou visível da borda superior da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Retorna:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou visível da borda esquerda da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Retorna:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou visível da borda esquerda da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou visível da borda direita da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Retorna:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou visível da borda direita da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

Traço Horizontal (padrão é false) - especifica o estado oculto ou visível de uma linha horizontal riscada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retorna:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

Traço Horizontal (padrão é false) - especifica o estado oculto ou visível de uma linha horizontal riscada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

Traço Vertical (padrão é false) - especifica o estado oculto ou visível de uma linha vertical riscada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Retorna:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

Traço Vertical (padrão é false) - especifica o estado oculto ou visível de uma linha vertical riscada.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

Traço Diagonal Inferior-Esquerda para Superior-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retorna:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

Traço Diagonal Inferior-Esquerda para Superior-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

Traço Diagonal Superior-Esquerda para Inferior-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retorna:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

Traço Diagonal Superior-Esquerda para Inferior-Direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de contorno.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |