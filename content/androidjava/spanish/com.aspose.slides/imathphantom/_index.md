---
title: IMathPhantom
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un objeto matemático fantasma ltmphantgt que afecta el diseño de su elemento hijo sin necesariamente mostrarlo.
type: docs
url: /es/com.aspose.slides/imathphantom/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Representa un objeto matemático fantasma (<m:phant>) que afecta el diseño de su elemento hijo sin necesariamente mostrarlo. Un fantasma puede ocultar su expresión base mientras conserva su ancho, altura o profundidad para alinear fórmulas o reservar espacio. La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, ZeroDesc y Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ocultar el contenido
>  phantom.setZeroWidth(false);     // Mantener el ancho
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getShow()](#getShow--) | Obtiene o establece un valor que indica si el elemento base se muestra. |
| [setShow(boolean value)](#setShow-boolean-) | Obtiene o establece un valor que indica si el elemento base se muestra. |
| [getZeroWidth()](#getZeroWidth--) | Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero. |
| [getZeroAsc()](#getZeroAsc--) | Obtiene o establece un valor que indica si la ascensión (altura sobre la línea base) del elemento base debe tratarse como cero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Obtiene o establece un valor que indica si la ascensión (altura sobre la línea base) del elemento base debe tratarse como cero. |
| [getZeroDesc()](#getZeroDesc--) | Obtiene o establece un valor que indica si la descensión (profundidad bajo la línea base) del elemento base debe tratarse como cero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Obtiene o establece un valor que indica si la descensión (profundidad bajo la línea base) del elemento base debe tratarse como cero. |
| [getTransp()](#getTransp--) | Obtiene o establece un valor que indica si el fantasma es transparente para las reglas de espaciado basadas en clases. |
| [setTransp(boolean value)](#setTransp-boolean-) | Obtiene o establece un valor que indica si el fantasma es transparente para las reglas de espaciado basadas en clases. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```


Obtiene o establece un valor que indica si el elemento base se muestra.

--------------------

Cuando es false, el elemento base está oculto pero puede seguir ocupando espacio según otras configuraciones del fantasma. Corresponde al atributo OMML m:show.

**Devuelve:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


Obtiene o establece un valor que indica si el elemento base se muestra.

--------------------

Cuando es false, el elemento base está oculto pero puede seguir ocupando espacio según otras configuraciones del fantasma. Corresponde al atributo OMML m:show.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no reserva espacio horizontal para su base. Corresponde al atributo OMML m:zeroWid.

**Devuelve:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no reserva espacio horizontal para su base. Corresponde al atributo OMML m:zeroWid.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


Obtiene o establece un valor que indica si la ascensión (altura sobre la línea base) del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no eleva la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroAsc.

**Devuelve:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


Obtiene o establece un valor que indica si la ascensión (altura sobre la línea base) del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no eleva la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroAsc.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


Obtiene o establece un valor que indica si la descensión (profundidad bajo la línea base) del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no baja la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroDesc.

**Devuelve:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


Obtiene o establece un valor que indica si la descensión (profundidad bajo la línea base) del elemento base debe tratarse como cero.

--------------------

Cuando es true, el fantasma no baja la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroDesc.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


Obtiene o establece un valor que indica si el fantasma es transparente para las reglas de espaciado basadas en clases.

--------------------

Cuando es true, los operadores y símbolos dentro del fantasma siguen afectando el espaciado matemático alrededor del fantasma (como si fuera visible). Cuando es false, se ignora el espaciado basado en clases. Corresponde al atributo OMML m:transp.

**Devuelve:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


Obtiene o establece un valor que indica si el fantasma es transparente para las reglas de espaciado basadas en clases.

--------------------

Cuando es true, los operadores y símbolos dentro del fantasma siguen afectando el espaciado matemático alrededor del fantasma (como si fuera visible). Cuando es false, se ignora el espaciado basado en clases. Corresponde al atributo OMML m:transp.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |