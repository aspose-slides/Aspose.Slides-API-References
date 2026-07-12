---
title: IMathBar
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Especifica la función de barra que consiste en un argumento base y una barra superior o inferior
type: docs
url: /es/com.aspose.slides/imathbar/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Especifica la función de barra, que consiste en un argumento base y una barra superior o inferior

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getPosition()](#getPosition--) | Posición de la línea de barra. |
| [setPosition(int value)](#setPosition-int-) | Posición de la línea de barra. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumento base

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Posición de la línea de barra. Predeterminado: Superior

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Posición de la línea de barra. Predeterminado: Superior

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |