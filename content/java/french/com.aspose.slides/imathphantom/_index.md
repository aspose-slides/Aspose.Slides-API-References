---
title: IMathPhantom
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un objet mathématique fantôme ltmphantgt qui influence la disposition de son élément enfant sans nécessairement l'afficher.
type: docs
url: /fr/com.aspose.slides/imathphantom/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Représente un objet mathématique fantôme (<m:phant>) qui influence la disposition de son élément enfant sans nécessairement l’afficher. Un fantôme peut masquer son expression de base tout en préservant sa largeur, sa hauteur ou sa profondeur afin d’aligner les formules ou de réserver de l’espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Masquer le contenu
>  phantom.setZeroWidth(false);     // Conserver la largeur
>  ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getShow()](#getShow--) | Obtient ou définit une valeur indiquant si l’élément de base est affiché. |
| [setShow(boolean value)](#setShow-boolean-) | Obtient ou définit une valeur indiquant si l’élément de base est affiché. |
| [getZeroWidth()](#getZeroWidth--) | Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être traitée comme nulle. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être traitée comme nulle. |
| [getZeroAsc()](#getZeroAsc--) | Obtient ou définit une valeur indiquant si la montée (hauteur au-dessus de la ligne de base) de l’élément de base doit être traitée comme nulle. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Obtient ou définit une valeur indiquant si la montée (hauteur au-dessus de la ligne de base) de l’élément de base doit être traitée comme nulle. |
| [getZeroDesc()](#getZeroDesc--) | Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être traitée comme nulle. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être traitée comme nulle. |
| [getTransp()](#getTransp--) | Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes. |
| [setTransp(boolean value)](#setTransp-boolean-) | Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```


Obtient ou définit une valeur indiquant si l’élément de base est affiché.

--------------------

Lorsque la valeur est false, l’élément de base est masqué mais peut encore occuper de l’espace selon d’autres paramètres du fantôme. Correspond à l’attribut OMML m:show.

**Renvoie :**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


Obtient ou définit une valeur indiquant si l’élément de base est affiché.

--------------------

Lorsque la valeur est false, l’élément de base est masqué mais peut encore occuper de l’espace selon d’autres paramètres du fantôme. Correspond à l’attribut OMML m:show.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme ne réserve pas d’espace horizontal pour sa base. Correspond à l’attribut OMML m:zeroWid.

**Renvoie :**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme ne réserve pas d’espace horizontal pour sa base. Correspond à l’attribut OMML m:zeroWid.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


Obtient ou définit une valeur indiquant si la montée (hauteur au-dessus de la ligne de base) de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme n’élève pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroAsc.

**Renvoie :**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


Obtient ou définit une valeur indiquant si la montée (hauteur au-dessus de la ligne de base) de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme n’élève pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroAsc.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme n’abaisse pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroDesc.

**Renvoie :**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être traitée comme nulle.

--------------------

Lorsque la valeur est true, le fantôme n’abaisse pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroDesc.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes.

--------------------

Lorsque la valeur est true, les opérateurs et symboles à l’intérieur du fantôme affectent toujours l’espacement mathématique autour du fantôme (comme s’il était visible). Lorsque la valeur est false, l’espacement basé sur les classes est ignoré. Correspond à l’attribut OMML m:transp.

**Renvoie :**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes.

--------------------

Lorsque la valeur est true, les opérateurs et symboles à l’intérieur du fantôme affectent toujours l’espacement mathématique autour du fantôme (comme s’il était visible). Lorsque la valeur est false, l’espacement basé sur les classes est ignoré. Correspond à l’attribut OMML m:transp.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |