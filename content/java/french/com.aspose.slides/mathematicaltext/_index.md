---
title: MathematicalText
second_title: Référence de l'API Aspose.Slides pour Java
description: Texte mathématique
type: docs
url: /fr/com.aspose.slides/mathematicaltext/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Texte mathématique

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Constructeur par défaut (crée la valeur String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Crée MathText avec un seul symbole |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Crée MathematicalText à partir du texte |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Crée MathematicalText à partir du texte et des paramètres de format |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Valeur du texte |
| [setValue(String value)](#setValue-java.lang.String-) | Valeur du texte |
| [getFormat()](#getFormat--) | Propriétés de formatage du texte |
| [getChildren()](#getChildren--) | Récupère les éléments enfants |

### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Constructeur par défaut (crée la valeur String.Empty)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Crée MathText avec un seul symbole

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char | symbole unique |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Crée MathematicalText à partir du texte

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Crée MathematicalText à partir du texte et des paramètres de format

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | paramètres de format du texte |

### getValue() {#getValue--}
```
public final String getValue()
```


Valeur du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Renvoie :**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Valeur du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Propriétés de formatage du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtient les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[]