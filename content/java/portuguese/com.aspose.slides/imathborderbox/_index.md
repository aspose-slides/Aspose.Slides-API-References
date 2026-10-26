---
title: IMathBorderBox
second_title: Referência da API Aspose.Slides para Java
description: Desenha um retângulo ou outra borda ao redor do IMathElement.
type: docs
url: /pt/com.aspose.slides/imathborderbox/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Desenha um retângulo ou outro tipo de borda ao redor do IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getHideTop()](#getHideTop--) | Ocultar borda superior (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Ocultar borda superior (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda. |
| [getHideBottom()](#getHideBottom--) | Ocultar borda inferior (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Ocultar borda inferior (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda. |
| [getHideLeft()](#getHideLeft--) | Ocultar borda esquerda (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Ocultar borda esquerda (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda. |
| [getHideRight()](#getHideRight--) | Ocultar borda direita (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Ocultar borda direita (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Riscado horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Riscado horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Riscado vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Riscado vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Riscado da parte inferior esquerda para a parte superior direita (padrão é false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Riscado da parte inferior esquerda para a parte superior direita (padrão é false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Riscado da parte superior esquerda para a parte inferior direita (padrão é false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Riscado da parte superior esquerda para a parte inferior direita (padrão é false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Exemplo:
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

Ocultar borda superior (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda superior (padrão é false) - especifica o estado oculto ou exibido da borda superior da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda inferior (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda inferior (padrão é false) - especifica o estado oculto ou exibido da borda inferior da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda esquerda (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda esquerda (padrão é false) - especifica o estado oculto ou exibido da borda esquerda da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda direita (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda.

--------------------

> ```
> Exemplo:
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

Ocultar borda direita (padrão é false) - especifica o estado oculto ou exibido da borda direita da caixa de borda.

--------------------

> ```
> Exemplo:
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

Riscado horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada.

--------------------

> ``` 
> Exemplo:
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

Riscado horizontal (padrão é false) - especifica o estado oculto ou exibido de uma linha horizontal riscada.

--------------------

> ```
> Exemplo:
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

Riscado vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada.

--------------------

> ```
> Exemplo:
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

Riscado vertical (padrão é false) - especifica o estado oculto ou exibido de uma linha vertical riscada.

--------------------

> ```
> Exemplo:
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

Riscado da parte inferior esquerda para a parte superior direita (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de borda.

--------------------

> ```
> Exemplo:
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

Riscado da parte inferior esquerda para a parte superior direita (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto inferior esquerdo ao canto superior direito da caixa de borda.

--------------------

> ```
> Exemplo:
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

Riscado da parte superior esquerda para a parte inferior direita (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de borda.

--------------------

> ```
> Exemplo:
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

Riscado da parte superior esquerda para a parte inferior direita (padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal riscada do canto superior esquerdo ao canto inferior direito da caixa de borda.

--------------------

> ```
> Exemplo:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |