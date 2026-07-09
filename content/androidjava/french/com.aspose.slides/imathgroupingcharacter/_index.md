---
title: IMathGroupingCharacter
second_title: Aspose.Slides pour Android via la référence API Java
description: Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments
type: docs
url: /fr/com.aspose.slides/imathgroupingcharacter/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Spécifie un symbole de regroupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getCharacter()](#getCharacter--) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Position of grouping character. |
| [setPosition(int value)](#setPosition-int-) | Position of grouping character. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertical justification of group character. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertical justification of group character. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument de base

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Retourne:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Position du caractère de groupe. Par défaut : Bas

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Retourne:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Position du caractère de groupe. Par défaut : Bas

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se trouve sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet se trouve sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Retourne:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)


Justification verticale du caractère de groupe. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupe est au-dessus de l'objet, VerticalJustification de Top indique que le haut de l'objet se situe sur la ligne de base ; lorsque VerticalJustification est réglé sur Bottom, le bas de l'objet est sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Exemple :
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |