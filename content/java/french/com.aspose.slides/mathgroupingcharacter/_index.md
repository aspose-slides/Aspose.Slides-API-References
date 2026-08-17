---
title: MathGroupingCharacter
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie un symbole de groupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments
type: docs
url: /fr/com.aspose.slides/mathgroupingcharacter/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Spécifie un symbole de groupement au-dessus ou en dessous d'une expression, généralement pour mettre en évidence la relation entre les éléments

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Constructeurs

| Constructor | Description |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Initialise une nouvelle instance de la classe MathGroupingCharacter avec le caractère de groupement par défaut U+23DF (ACCOLADE INFÉRIEURE) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Initialise une nouvelle instance de la classe MathGroupingCharacter. |
## Méthodes

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getCharacter()](#getCharacter--) | Caractère de groupement Valeur par défaut : U+23DF (ACCOLADE INFÉRIEURE) |
| [setCharacter(char value)](#setCharacter-char-) | Caractère de groupement Valeur par défaut : U+23DF (ACCOLADE INFÉRIEURE) |
| [getPosition()](#getPosition--) | Position du caractère de groupement. |
| [setPosition(int value)](#setPosition-int-) | Position du caractère de groupement. |
| [getVerticalJustification()](#getVerticalJustification--) | Justification verticale du caractère de groupement. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justification verticale du caractère de groupement. |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Initialise une nouvelle instance de la classe MathGroupingCharacter avec le caractère de groupement par défaut U+23DF (ACCOLADE INFÉRIEURE)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la barre est appliquée |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Initialise une nouvelle instance de la classe MathGroupingCharacter.

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la barre est appliquée |
| character | char | Caractère de groupement |
| position | int | Position du caractère de groupement |
| verticalJustification | int | Justification verticale du caractère de groupement |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de base

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Renvoie:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Caractère de groupement Valeur par défaut : U+23DF (ACCOLADE INFÉRIEURE)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```

**Renvoie:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Caractère de groupement Valeur par défaut : U+23DF (ACCOLADE INFÉRIEURE)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parenthèse inférieure
> ```


**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Position du caractère de groupement. Valeur par défaut : Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Renvoie:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Position du caractère de groupement. Valeur par défaut : Bottom

--------------------

> ```
> Exemple:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```


**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Justification verticale du caractère de groupement. Spécifie l’alignement de l’objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupement est au-dessus de l’objet, la JustificationVerticale Top indique que le haut de l’objet repose sur la ligne de base ; lorsque la JustificationVerticale est définie sur Bottom, le bas de l’objet est sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Renvoie:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```

Justification verticale du caractère de groupement. Spécifie l’alignement de l’objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupement est au-dessus de l’objet, la JustificationVerticale Top indique que le haut de l’objet repose sur la ligne de base ; lorsque la JustificationVerticale est définie sur Bottom, le bas de l’objet est sur la ligne de base. Valeur par défaut : Bottom pour Position=Top, et Top pour Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Renvoie:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés du caractère de contrôle

**Renvoie:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps