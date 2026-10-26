---
title: IMathematicalTextFactory
second_title: Aspose.Slides pour Android via la référence de l'API Java
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
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Créer un élément de texte mathématique vide avec la valeur spécifiée et les propriétés de mise en forme |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Créer un élément de texte mathématique vide

**Retourne :**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau texte mathématique
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Créer un élément de texte mathématique avec la valeur spécifiée

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| mathSymbol | char | symbole unique à utiliser comme valeur de texte |

**Retourne :**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau texte mathématique
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Créer un élément de texte mathématique vide avec la valeur spécifiée

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |

**Retourne :**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau texte mathématique
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Créer un élément de texte mathématique vide avec la valeur spécifiée et les propriétés de mise en forme

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | valeur du texte |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | paramètres de format du texte |

**Retourne :**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nouveau texte mathématique