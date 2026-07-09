---
title: IMathPhantom
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un objet mathématique fantôme ltmphantgt qui affecte la mise en page de son élément enfant sans nécessairement l'afficher.
type: docs
url: /fr/com.aspose.slides/imathphantom/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Représente un objet mathématique fantôme (<m:phant>) qui influence la mise en page de son élément enfant sans nécessairement l’afficher. Un fantôme peut masquer son expression de base tout en préservant sa largeur, sa hauteur ou sa profondeur afin d’aligner les formules ou de réserver de l’espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Masquer le contenu
>  phantom.setZeroWidth(false);     // Conserver la largeur
>  ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Gets or sets a value indicating whether the base element is displayed. |
| [setShow(boolean value)](#setShow-boolean-) | Gets or sets a value indicating whether the base element is displayed. |
| [getZeroWidth()](#getZeroWidth--) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [getZeroAsc()](#getZeroAsc--) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [getZeroDesc()](#getZeroDesc--) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [getTransp()](#getTransp--) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [setTransp(boolean value)](#setTransp-boolean-) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```
Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Returns:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Returns:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Returns:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Returns:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**Returns:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)


Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes.

--------------------

Lorsque la valeur est vraie, les opérateurs et symboles à l’intérieur du fantôme influencent toujours l’espacement mathématique autour du fantôme (comme s’il était visible). Lorsque la valeur est fausse, l’espacement basé sur les classes est ignoré. Correspond à l’attribut OMML m:transp.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |