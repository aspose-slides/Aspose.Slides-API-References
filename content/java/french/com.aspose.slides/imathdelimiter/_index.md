---
title: IMathDelimiter
second_title: Référence API Aspose.Slides pour Java
description: Spécifie l'objet délimiteur composé de caractères d'ouverture et de fermeture tels que les parenthèses, les accolades, les crochets et les barres verticales, ainsi que d'un ou plusieurs éléments mathématiques à l'intérieur séparés par un caractère spécifié.
type: docs
url: /fr/com.aspose.slides/imathdelimiter/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses, accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (\\ud835\\udc652) ; [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character spécifie le caractère de début, ou d'ouverture, du délimiteur. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character spécifie le caractère de début, ou d'ouverture, du délimiteur. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifie la forme des délimiteurs dans l'objet délimiteur. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifie la forme des délimiteurs dans l'objet délimiteur. |
| [delimit(char separatorCharacter)](#delimit-char-) | Délimite les arguments en utilisant le caractère délimiteur spécifié |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Renvoie :**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character spécifie le caractère de début, ou d'ouverture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Renvoie :**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character spécifie le caractère de début, ou d'ouverture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Renvoie :**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character spécifie le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Renvoie :**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character spécifie le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

Specifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. Valeur par défaut : true

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Renvoie :**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```

Specifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de leur opérande. Valeur par défaut : true

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

Specifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour occuper toute la hauteur de leur contenu. Lorsque MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Renvoie :**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public abstract void setDelimiterShape(int value)
```

Specifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour occuper toute la hauteur de leur contenu. Lorsque MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Délimite les arguments en utilisant le caractère délimiteur spécifié

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | caractère délimiteur |

**Renvoie :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Cet objet après application du caractère délimiteur