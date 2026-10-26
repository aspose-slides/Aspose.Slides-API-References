---
title: IMathGroupingCharacter
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un symbole de groupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments
type: docs
url: /fr/com.aspose.slides/imathgroupingcharacter/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Spécifie un symbole de groupement au-dessus ou au-dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getCharacter()](#getCharacter--) | Caractère de groupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Caractère de groupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position du caractère de groupement. |
| [setPosition(int value)](#setPosition-int-) | Position du caractère de groupement. |
| [getVerticalJustification()](#getVerticalJustification--) | Justification verticale du caractère de groupe. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justification verticale du caractère de groupe. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Retour :**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Caractère de groupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```

**Retour :**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Caractère de groupement Valeur par défaut : U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Position du caractère de groupement. Valeur par défaut : Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Retour :**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Position du caractère de groupement. Valeur par défaut : Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe se trouve au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Retour :**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe se trouve au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |