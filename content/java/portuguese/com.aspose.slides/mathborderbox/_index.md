---
title: MathBorderBox
second_title: Referência da API Aspose.Slides para Java
description: Desenha uma borda retangular ou outra ao redor do IMathElement.
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

Desenha uma borda retangular ou outra em torno do IMathElement.

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
| [getBase()](#getBase--) | Argumento base |
| [getHideTop()](#getHideTop--) | Hide Top Edge (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (padrão é false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (padrão é false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (padrão é false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (padrão é false). |
| [getChildren()](#getChildren--) | Obter elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracteres de Controle |
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
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Strikethrough Horizontal |
| strikethroughVertical | boolean | Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Strikethrough Top-Left to Bottom-Right |

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

Hide Top Edge (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda.

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

Hide Top Edge (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda.

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

Hide Bottom Edge (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda.

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

Hide Bottom Edge (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda.

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

Hide Left Edge (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda.

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

Hide Left Edge (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda.

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

Hide Right Edge (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda.

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

Hide Right Edge (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda.

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

Strikethrough Horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada.

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

Strikethrough Horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada.

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

Strikethrough Vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada.

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

Strikethrough Vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada.

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

Strikethrough Bottom-Left to Top-Right (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de borda.

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

Strikethrough Bottom-Left to Top-Right (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de borda.

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

Strikethrough Top-Left to Bottom-Right (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de borda.

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

Strikethrough Top-Left to Bottom-Right (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de borda.

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

Propriedades de Caracteres de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps