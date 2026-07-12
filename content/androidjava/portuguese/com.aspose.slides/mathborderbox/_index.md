---
title: MathBorderBox
second_title: Aspose.Slides para Android via Referência da API Java
description: Desenha uma borda retangular ou outro tipo de borda ao redor do IMathElement.
type: docs
url: /pt/com.aspose.slides/mathborderbox/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Desenha uma borda retangular ou outro tipo de borda ao redor do IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Cria o elemento MathBorderBox com borda retangular |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Cria o elemento MathBorderBox |
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


Cria o elemento MathBorderBox com borda retangular

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O elemento base ao qual a caixa de borda é aplicada. Pode ser nulo. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Cria o elemento MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | O elemento base ao qual a caixa de borda é aplicada |
| hideTop | boolean | Ocultar Borda Superior |
| hideBottom | boolean | Ocultar Borda Inferior |
| hideLeft | boolean | Ocultar Borda Esquerda |
| hideRight | boolean | Ocultar Borda Direita |
| strikethroughHorizontal | boolean | Riscado Horizontal |
| strikethroughVertical | boolean | Riscado Vertical |
| strikethroughBottomLeftToTopRight | boolean | Riscado da Inferior-Esquerda para a Superior-Direita |
| strikethroughTopLeftToBottomRight | boolean | Riscado da Superior-Esquerda para a Inferior-Direita |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou mostrado da borda superior da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Retorna:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


Ocultar Borda Superior (padrão é false) - especifica o estado oculto ou mostrado da borda superior da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou mostrado da borda inferior da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Retorna:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


Ocultar Borda Inferior (padrão é false) - especifica o estado oculto ou mostrado da borda inferior da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou mostrado da borda esquerda da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Retorna:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


Ocultar Borda Esquerda (padrão é false) - especifica o estado oculto ou mostrado da borda esquerda da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou mostrado da borda direita da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Retorna:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


Ocultar Borda Direita (padrão é false) - especifica o estado oculto ou mostrado da borda direita da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


Riscado Horizontal (padrão é false) - especifica o estado oculto ou mostrado de uma linha de risco horizontal.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Retorna:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


Riscado Horizontal (padrão é false) - especifica o estado oculto ou mostrado de uma linha de risco horizontal.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


Riscado Vertical (padrão é false) - especifica o estado oculto ou mostrado de uma linha de risco vertical.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Retorna:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


Riscado Vertical (padrão é false) - especifica o estado oculto ou mostrado de uma linha de risco vertical.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


Riscado da Inferior-Esquerda para a Superior-Direita (padrão é false). Especifica o estado oculto ou mostrado de uma linha diagonal riscosa do canto inferior-esquerdo ao canto superior-direito da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Retorna:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


Riscado da Inferior-Esquerda para a Superior-Direita (padrão é false). Especifica o estado oculto ou mostrado de uma linha diagonal riscosa do canto inferior-esquerdo ao canto superior-direito da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


Riscado da Superior-Esquerda para a Inferior-Direita (padrão é false). Especifica o estado oculto ou mostrado de uma linha diagonal riscosa do canto superior-esquerdo ao canto inferior-direito da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Retorna:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


Riscado da Superior-Esquerda para a Inferior-Direita (padrão é false). Especifica o estado oculto ou mostrado de uma linha diagonal riscosa do canto superior-esquerdo ao canto inferior-direito da caixa de borda.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriedades de Caracter de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps