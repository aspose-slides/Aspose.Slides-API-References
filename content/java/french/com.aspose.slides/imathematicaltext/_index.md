---
title: IMathematicalText
second_title: Référence de l'API Aspose.Slides pour Java
description: Texte mathématique
type: docs
url: /fr/com.aspose.slides/imathematicaltext/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Texte mathématique

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Valeur du texte |
| [setValue(String value)](#setValue-java.lang.String-) | Valeur du texte |
| [getFormat()](#getFormat--) | Propriétés de formatage du texte |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Valeur du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Retour:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


Valeur du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


Propriétés de formatage du texte

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat)