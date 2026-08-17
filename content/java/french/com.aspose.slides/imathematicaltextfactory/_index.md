---
title: IMathematicalTextFactory
second_title: Référence de l'API Aspose.Slides for Java
description: Permet de créer un élément MathematicalText
type: docs
url: /fr/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Permet de créer un élément MathematicalText

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Créer un élément de texte mathématique vide |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Créer un élément de texte mathématique avec la valeur spécifiée |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Créer un élément de texte mathématique vide avec la valeur spécifiée |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Créer un élément de texte mathématique vide avec la valeur spécifiée et les propriétés de formatage |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Créer un élément MathematicalText vide

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Créer un élément de texte mathématique avec la valeur spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char | symbole unique à utiliser comme valeur de texte |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Créer un élément MathematicalText vide avec la valeur spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Créer un élément MathematicalText vide avec la valeur spécifiée et les propriétés de formatage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | paramètres de format du texte |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau Mathematical Text