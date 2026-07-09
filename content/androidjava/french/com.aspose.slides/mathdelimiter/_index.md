---
title: MathDelimiter
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Spécifie l’objet délimiteur composé de caractères d’ouverture et de fermeture tels que les parenthèses, les accolades, les crochets et les barres verticales, ainsi que d’un ou plusieurs éléments mathématiques à l’intérieur, séparés par un caractère spécifié.
type: docs
url: /fr/com.aspose.slides/mathdelimiter/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Spécifie l’objet délimiteur, composé de caractères d’ouverture et de fermeture (tels que les parenthèses, accolades, crochets et barres verticales), ainsi que d’un ou plusieurs éléments mathématiques à l’intérieur, séparés par un caractère spécifié. Exemples : (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Initializes MathDelimiter with the specified element as single base argument |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | One or more mathematical elements separated by delimiter characters |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character specifies the ending, or closing, delimiter character. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. |
| [getDelimiterShape()](#getDelimiterShape--) | Specifies the shape of delimiters in the delimiter object. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Specifies the shape of delimiters in the delimiter object. |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits arguments using the specified delimiter character |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Initializes MathDelimiter with the specified element as single base argument

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base element to which the delimiter is applied. Can be null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

One or more mathematical elements separated by delimiter characters

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Le caractère de début du délimiteur indique le caractère de délimiteur de début, ou d'ouverture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : '('.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Retourne:** 
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Le caractère de début du délimiteur indique le caractère de début, ou d'ouverture, du délimiteur. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : '('.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Returns:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Le caractère séparateur du délimiteur spécifie le caractère qui sépare les arguments dans l'objet délimiteur. Valeur par défaut : '|'.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
>  ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Le caractère de fin du délimiteur indique le caractère de délimiteur de fin, ou de fermeture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : ')'.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
>  ```

**Retourne:** 
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Le caractère de fin du délimiteur indique le caractère de délimiteur de fin, ou de fermeture. Les délimiteurs mathématiques sont des caractères d'encadrement tels que les parenthèses, les crochets et les accolades. Valeur par défaut : ')'.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque true, les délimiteurs grandissent verticalement pour correspondre à la hauteur de l'opérande. La valeur par défaut est true

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Retourne:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Spécifie la croissance de BeginningCharacter, SeparatorCharacter, EndingCharacter. Lorsque true, les délimiteurs grandissent verticalement pour correspondre à la hauteur de l'opérande. La valeur par défaut est true

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque la valeur est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent être ajustés pour s'adapter à la hauteur totale de leur contenu. Lorsque la valeur est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
>  ```

**Retourne:** 
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque la valeur est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent être ajustés pour correspondre à la hauteur totale de leur contenu. Lorsque la valeur est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

--------------------

> ```
> Exemple:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Paramètres:**
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

**Retourne :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Cet objet après l'application du caractère délimiteur
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement crochet ouvrant) |
| endingCharacter | char | Caractère de fin (généralement crochet fermant) |

**Retourne:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Si beginningCharacter et endingCharacter sont null, les propriétés correspondantes sont uniquement assignées et aucun nouvel objet n'est créé (renvoie cette instance). Sinon, renvoie un nouvel élément mathématique de type Delimiter qui inclut les caractères spécifiés comme encadrement et cette instance de [MathDelimiter](../../com.aspose.slides/mathdelimiter) encadrée à l'intérieur.
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Get children elements

**Returns:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps