---
title: MathPhantom
second_title: Référence API Aspose.Slides pour Java
description: Représente un objet mathématique fantôme ltmphantgt qui affecte la disposition de son élément enfant sans nécessairement l'afficher.
type: docs
url: /fr/com.aspose.slides/mathphantom/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Représente un objet mathématique fantôme (<m:phant>) qui influence la disposition de son élément enfant sans nécessairement l’afficher. Un fantôme peut masquer son expression de base tout en conservant sa largeur, sa hauteur ou sa profondeur afin d’aligner les formules ou de réserver de l’espace. La visibilité et le comportement géométrique sont contrôlés par des propriétés telles que Show, ZeroWid, ZeroAsc, ZeroDesc et Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Masquer le contenu
>  phantom.setZeroWidth(false);     // Conserver la largeur
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe [MathPhantom](../../com.aspose.slides/mathphantom) en utilisant l’élément mathématique de base spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getShow()](#getShow--) | Obtient ou définit une valeur indiquant si l’élément de base est affiché. |
| [setShow(boolean value)](#setShow-boolean-) | Obtient ou définit une valeur indiquant si l’élément de base est affiché. |
| [getZeroWidth()](#getZeroWidth--) | Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être considérée comme zéro. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être considérée comme zéro. |
| [getZeroAsc()](#getZeroAsc--) | Obtient ou définit une valeur indiquant si l’ascension (hauteur au-dessus de la ligne de base) de l’élément de base doit être considérée comme zéro. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Obtient ou définit une valeur indiquant si l’ascension (hauteur au-dessus de la ligne de base) de l’élément de base doit être considérée comme zéro. |
| [getZeroDesc()](#getZeroDesc--) | Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être considérée comme zéro. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être considérée comme zéro. |
| [getTransp()](#getTransp--) | Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes. |
| [setTransp(boolean value)](#setTransp-boolean-) | Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés de caractère de contrôle |
| [getChildren()](#getChildren--) | Récupère les éléments enfants |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Initialise une nouvelle instance de la classe [MathPhantom](../../com.aspose.slides/mathphantom) en utilisant l’élément mathématique de base spécifié.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Le [IMathElement](../../com.aspose.slides/imathelement) de base dont la **visibilité** et la **mise en page** seront contrôlées **par le fantôme**. Cet élément définit le contenu qui peut être masqué ou affiché, tout en affectant l’**alignement** géométrique des mathématiques environnantes.

--------------------

L’élément fantôme est utilisé pour réserver ou supprimer l’espace visuel de son expression de base sans nécessairement l’afficher. Il correspond à l’élément OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de base

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Valeur de retour:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Obtient ou définit une valeur indiquant si l’élément de base est affiché.

--------------------

Lorsque false, l’élément de base est masqué mais peut toujours occuper de l’espace selon d’autres paramètres du fantôme. Correspond à l’attribut OMML m:show.

**Valeur de retour:**  
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Obtient ou définit une valeur indiquant si l’élément de base est affiché.

--------------------

Lorsque false, l’élément de base est masqué mais peut toujours occuper de l’espace selon d’autres paramètres du fantôme. Correspond à l’attribut OMML m:show.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme ne réserve pas d’espace horizontal pour sa base. Correspond à l’attribut OMML m:zeroWid.

**Valeur de retour:**  
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Obtient ou définit une valeur indiquant si la largeur de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme ne réserve pas d’espace horizontal pour sa base. Correspond à l’attribut OMML m:zeroWid.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Obtient ou définit une valeur indiquant si l’ascension (hauteur au-dessus de la ligne de base) de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme ne soulève pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroAsc.

**Valeur de retour:**  
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Obtient ou définit une valeur indiquant si l’ascension (hauteur au-dessus de la ligne de base) de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme ne soulève pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroAsc.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme n’abaisse pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroDesc.

**Valeur de retour:**  
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Obtient ou définit une valeur indiquant si la descente (profondeur sous la ligne de base) de l’élément de base doit être considérée comme zéro.

--------------------

Lorsque true, le fantôme n’abaisse pas la ligne de base de la ligne mathématique environnante. Correspond à l’attribut OMML m:zeroDesc.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes.

--------------------

Lorsque true, les opérateurs et symboles à l’intérieur du fantôme affectent toujours l’espacement mathématique autour du fantôme (comme s’ils étaient visibles). Lorsque false, l’espacement basé sur les classes est ignoré. Correspond à l’attribut OMML m:transp.

**Valeur de retour:**  
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Obtient ou définit une valeur indiquant si le fantôme est transparent pour les règles d’espacement basées sur les classes.

--------------------

Lorsque true, les opérateurs et symboles à l’intérieur du fantôme affectent toujours l’espacement mathématique autour du fantôme (comme s’ils étaient visibles). Lorsque false, l’espacement basé sur les classes est ignoré. Correspond à l’attribut OMML m:transp.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés de caractère de contrôle

**Valeur de retour:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Récupère les éléments enfants

**Valeur de retour:**  
com.aspose.slides.IMathElement[]