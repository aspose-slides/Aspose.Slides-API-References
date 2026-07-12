---
title: MathPhantom
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un objeto matemático fantasma ltmphantgt que afecta el diseño de su elemento hijo sin necesidad de mostrarlo.
type: docs
url: /es/com.aspose.slides/mathphantom/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Representa un objeto matemático fantasma (<m:phant>) que afecta la disposición de su elemento hijo sin necesariamente mostrarlo. Un fantasma puede ocultar su expresión base mientras conserva su ancho, altura o profundidad para alinear fórmulas o reservar espacio. La visibilidad y el comportamiento geométrico se controlan mediante propiedades como Show, ZeroWid, ZeroAsc, ZeroDesc y Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ocultar el contenido
>  phantom.setZeroWidth(false);     // Mantener el ancho
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase [MathPhantom](../../com.aspose.slides/mathphantom) usando el elemento matemático base especificado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getShow()](#getShow--) | Obtiene o establece un valor que indica si el elemento base se muestra. |
| [setShow(boolean value)](#setShow-boolean-) | Obtiene o establece un valor que indica si el elemento base se muestra. |
| [getZeroWidth()](#getZeroWidth--) | Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero. |
| [getZeroAsc()](#getZeroAsc--) | Obtiene o establece un valor que indica si la ascensión (altura encima de la línea base) del elemento base debe tratarse como cero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Obtiene o establece un valor que indica si la ascensión (altura encima de la línea base) del elemento base debe tratarse como cero. |
| [getZeroDesc()](#getZeroDesc--) | Obtiene o establece un valor que indica si la bajada (profundidad debajo de la línea base) del elemento base debe tratarse como cero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Obtiene o establece un valor que indica si la bajada (profundidad debajo de la línea base) del elemento base debe tratarse como cero. |
| [getTransp()](#getTransp--) | Obtiene o establece un valor que indica si el fantasma es transparente para reglas de espaciado basadas en clases. |
| [setTransp(boolean value)](#setTransp-boolean-) | Obtiene o establece un valor que indica si el fantasma es transparente para reglas de espaciado basadas en clases. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de carácter de control |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Inicializa una nueva instancia de la clase [MathPhantom](../../com.aspose.slides/mathphantom) usando el elemento matemático base especificado.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El [IMathElement](../../com.aspose.slides/imathelement) base cuya visibilidad y disposición serán controladas por el fantasma. Este elemento define el contenido que puede ocultarse o mostrarse, mientras sigue afectando la alineación geométrica de la matemática circundante. |

El elemento fantasma se utiliza para reservar o suprimir el espacio visual de su expresión base sin necesariamente mostrarlo. Corresponde al elemento OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final boolean getShow()
```

Obtiene o establece un valor que indica si el elemento base se muestra.

Cuando es false, el elemento base está oculto pero aún puede ocupar espacio dependiendo de otras configuraciones del fantasma. Corresponde al atributo OMML m:show.

**Devuelve:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Obtiene o establece un valor que indica si el elemento base se muestra.

Cuando es false, el elemento base está oculto pero aún puede ocupar espacio dependiendo de otras configuraciones del fantasma. Corresponde al atributo OMML m:show.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero.

Cuando es true, el fantasma no reserva espacio horizontal para su base. Corresponde al atributo OMML m:zeroWid.

**Devuelve:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Obtiene o establece un valor que indica si el ancho del elemento base debe tratarse como cero.

Cuando es true, el fantasma no reserva espacio horizontal para su base. Corresponde al atributo OMML m:zeroWid.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Obtiene o establece un valor que indica si la ascensión (altura encima de la línea base) del elemento base debe tratarse como cero.

Cuando es true, el fantasma no eleva la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroAsc.

**Devuelve:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Obtiene o establece un valor que indica si la ascensión (altura encima de la línea base) del elemento base debe tratarse como cero.

Cuando es true, el fantasma no eleva la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroAsc.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Obtiene o establece un valor que indica si la bajada (profundidad debajo de la línea base) del elemento base debe tratarse como cero.

Cuando es true, el fantasma no baja la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroDesc.

**Devuelve:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Obtiene o establece un valor que indica si la bajada (profundidad debajo de la línea base) del elemento base debe tratarse como cero.

Cuando es true, el fantasma no baja la línea base de la línea matemática circundante. Corresponde al atributo OMML m:zeroDesc.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Obtiene o establece un valor que indica si el fantasma es transparente para reglas de espaciado basadas en clases.

Cuando es true, los operadores y símbolos dentro del fantasma siguen afectando el espaciado matemático alrededor del fantasma (como si fuera visible). Cuando es false, se ignora el espaciado basado en clases. Corresponde al atributo OMML m:transp.

**Devuelve:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Obtiene o establece un valor que indica si el fantasma es transparente para reglas de espaciado basadas en clases.

Cuando es true, los operadores y símbolos dentro del fantasma siguen afectando el espaciado matemático alrededor del fantasma (como si fuera visible). Cuando es false, se ignora el espaciado basado en clases. Corresponde al atributo OMML m:transp.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propiedades de carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]