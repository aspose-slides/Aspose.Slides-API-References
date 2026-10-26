---
title: MathDelimiter
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l'objet délimiteur composé de caractères d'ouverture et de fermeture tels que les parenthèses, les accolades, les crochets et les barres verticales, ainsi que d'un ou plusieurs éléments mathématiques à l'intérieur séparés par un caractère spécifié.
type: docs
url: /fr/com.aspose.slides/mathdelimiter/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Spécifie l'objet délimiteur, composé de caractères d'ouverture et de fermeture (tels que les parenthèses, accolades, crochets et barres verticales), et d'un ou plusieurs éléments mathématiques à l'intérieur, séparés par un caractère spécifié. Exemples : (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
>  ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initialise MathDelimiter avec l'élément spécifié en tant qu'argument de base unique |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArguments()](#getArguments--) | Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs |
| [getBeginningCharacter()](#getBeginningCharacter--) | Le caractère de début du délimiteur indique le caractère de début, ou d'ouverture, du délimiteur. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Le caractère de début du délimiteur indique le caractère de début, ou d'ouverture, du délimiteur. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Le caractère séparateur du délimiteur indique le caractère qui sépare les arguments dans l'objet délimiteur. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Le caractère séparateur du délimiteur indique le caractère qui sépare les arguments dans l'objet délimiteur. |
| [getEndingCharacter()](#getEndingCharacter--) | Le caractère de fin du délimiteur indique le caractère de fin, ou de fermeture, du délimiteur. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Le caractère de fin du délimiteur indique le caractère de fin, ou de fermeture, du délimiteur. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Spécifie la croissance des caractères de début, séparateur et fin. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de l'opérande. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Spécifie la croissance des caractères de début, séparateur et fin. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de l'opérande. |
| [getDelimiterShape()](#getDelimiterShape--) | Spécifie la forme des délimiteurs dans l'objet délimiteur. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Spécifie la forme des délimiteurs dans l'objet délimiteur. |
| [delimit(char separatorCharacter)](#delimit-char-) | Délimite les arguments en utilisant le caractère délimiteur spécifié |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encapsule un élément mathématique dans les caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [getChildren()](#getChildren--) | Obtient les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initialise MathDelimiter avec l'élément spécifié en tant qu'argument de base unique

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel le délimiteur est appliqué. Peut être nul. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Un ou plusieurs éléments mathématiques séparés par des caractères délimiteurs

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Retour :**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Le caractère de début du délimiteur indique le caractère de début, ou d'ouverture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Retour :**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Le caractère de début du délimiteur indique le caractère de début, ou d'ouverture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : '('.

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
public final char getSeparatorCharacter()
```

Le caractère séparateur du délimiteur indique le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Retour :**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Le caractère séparateur du délimiteur indique le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'.

--------------------

> ```
> Example:
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
public final char getEndingCharacter()
```

Le caractère de fin du délimiteur indique le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Retour :**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Le caractère de fin du délimiteur indique le caractère de fin, ou de fermeture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, crochets et accolades. Valeur par défaut : ')'.

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
public final boolean getGrowToMatchOperandHeight()
```

Spécifie la croissance des caractères de début, séparateur et fin. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de l'opérande. Valeur par défaut : true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retour :**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Spécifie la croissance des caractères de début, séparateur et fin. Lorsque vrai, les délimiteurs s'étendent verticalement pour correspondre à la hauteur de l'opérande. Valeur par défaut : true

--------------------

> ```
> Example:
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
public final int getDelimiterShape()
```

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque la forme est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte et sont adaptés à la hauteur totale de leur contenu. Lorsque la forme est MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu.

--------------------

> ```
> Exemple :
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Retour :**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque la forme est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte et sont adaptés à la hauteur totale de leur contenu. Lorsque la forme est MathDelimiterShape.Match, leur hauteur et forme sont modifiées pour correspondre exactement à leur contenu.

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
public final IMathDelimiter delimit(char separatorCharacter)
```

Délimite les arguments en utilisant le caractère délimiteur spécifié

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | caractère délimiteur |

**Retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Cet objet après l'application du caractère délimiteur
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encapsule un élément mathématique dans les caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement une parenthèse ouvrante) |
| endingCharacter | char | Caractère de fin (généralement une parenthèse fermante) |

**Retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Si beginningCharacter et endingCharacter sont null, les propriétés correspondantes sont assignées uniquement et aucun nouveau objet n'est créé (retourne cette instance). Sinon, retourne un nouvel élément mathématique de type Delimiter incluant les caractères spécifiés comme encadrement et cette instance de [MathDelimiter](../../com.aspose.slides/mathdelimiter) encadrée à l'intérieur.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtient les éléments enfants

**Retour :**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés du caractère de contrôle

**Retour :**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps