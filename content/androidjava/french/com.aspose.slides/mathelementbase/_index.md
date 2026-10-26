---
title: MathElementBase
second_title: Aspose.Slides pour Android via la référence API Java
description: Classe de base pour IMathElement avec l'implémentation de certaines méthodes communes à toutes les classes héritées. À usage interne uniquement.
type: docs
url: /fr/com.aspose.slides/mathelementbase/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Classe de base pour IMathElement avec l'implémentation de certaines méthodes communes à toutes les classes héritées. À usage interne uniquement. La classe héritée doit être IMathElement.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Renvoie l'objet Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joint un élément mathématique et forme un bloc mathématique |
| [join(String mathText)](#join-java.lang.String-) | Joint un texte mathématique et forme un bloc mathématique |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [divide(String denominator)](#divide-java.lang.String-) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [enclose()](#enclose--) | Encadre un élément mathématique entre parenthèses |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [function(String functionArgument)](#function-java.lang.String-) | Prend une fonction d'un argument en utilisant cette instance comme nom de fonction |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Prend la fonction spécifiée en utilisant cette instance comme argument |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Crée un indice |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Crée un indice |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Crée un exposant |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Crée un exposant |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée indice et exposant à droite |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Crée indice et exposant à droite |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée indice et exposant à gauche |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Crée indice et exposant à gauche |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [radical(String degree)](#radical-java.lang.String-) | Spécifie la racine mathématique du degré donné à partir de l'argument spécifié. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Prend la limite supérieure |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Prend la limite supérieure |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Prend la limite inférieure |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Prend la limite inférieure |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée un opérateur N-aire |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Crée un opérateur N-aire |
| [toMathArray()](#toMathArray--) | Place dans un tableau vertical |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Prend l'intégrale |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Prend l'intégrale |
| [integral(int integralType)](#integral-int-) | Prend l'intégrale sans limites |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Prend l'intégrale |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Prend l'intégrale |
| [accent(char accentCharacter)](#accent-char-) | Définit un accent (un caractère au-dessus de cet élément) |
| [overbar()](#overbar--) | Dessine une barre au-dessus de cet élément |
| [underbar()](#underbar--) | Dessine une barre au-dessous de cet élément |
| [group()](#group--) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre |
| [toBorderBox()](#toBorderBox--) | Place cet élément dans une boîte à bordure |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Place cet élément dans une boîte à bordure |
| [toBox()](#toBox--) | Place cet élément dans une boîte non visuelle (groupement logique) utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Joint un élément mathématique et forme un bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | The element to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Joint un texte mathématique et forme un bloc mathématique

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Texte mathématique à joindre |

**Retour :**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nouveau IMathBlock contenant cette instance et l'argument spécifié
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Creates a fraction with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Crée une fraction avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Exemple :
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Denominator |

**Retour :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Exemple :
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Retour :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Creates a fraction of the specified type with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Denominator |
| fractionType | int | Fraction type: Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Encloses a math element in parenthesis

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
>  ```

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes the parenthesis
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre un élément mathématique avec des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement le crochet ouvrant) |
| endingCharacter | char | Caractère de fin (généralement le crochet fermant) |

**Retour :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les caractères spécifiés comme encadrement
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```
Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Exemple :
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Un argument de la fonction |

**Retour :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Takes a function of an argument using this instance as the function name

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | An argument of the function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple :
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Function name |

**Retour :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouveau élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Takes specified function using this instance as the argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Function name |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Exemple :
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | L'un des types de fonction communs d'un argument |

**Retour :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```
Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

--------------------

> ```
> Exemple :
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retourne le logarithme de 'x' à la base '5'
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Additional argument depending on the type of function |

**Retour :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

--------------------

> ```
> Exemple :
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retourne le logarithme de 'x' à la base '5'
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Additional argument depending on the type of function |

**Retour :**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crée un indice

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |

**Retour :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```
Crée un indice

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |

**Retour :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Crée un exposant

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Retour :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouvel élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Crée un exposant

--------------------

> ```
> Exemple :
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Exposant (indice supérieur à droite) |

**Retour :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouvel élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the right

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the right) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the right) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Creates subscript and superscript on the right

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - New math element of type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Crée un indice et un exposant à gauche

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```
Creates subscript and superscript on the left

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - New math element of type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument du radical |

**Retour :**
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance du type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Specifies the mathematical root of the given degree from the specified argument.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Prend la limite supérieure

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retour :**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```
 


Prend la limite supérieure

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retour :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Prend la limite inférieure

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retour :**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Prend la limite inférieure

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retour :**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance du type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Crée un opérateur N-aire

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Crée un opérateur N-aire

--------------------

> ```
> Exemple :
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Le type d'opérateur N-aire |
| lowerLimit | java.lang.String | La limite inférieure |
| upperLimit | java.lang.String | La limite supérieure |

**Retour :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```
Place dans un tableau vertical

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
>  ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Takes the integral

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Retour :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```
Prend l'intégrale sans limites

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |

**Retour :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
>  ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Type d'intégrale |
| lowerLimit | java.lang.String | Limite inférieure de l'intégrale |
| upperLimit | java.lang.String | Limite supérieure de l'intégrale |
| limitLocations | int | emplacement des limites |

**Retour :**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance du type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Prend l'intégrale

--------------------

> ```
> Exemple :
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Sets an accent mark (a character on the top of this element)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Returns:**
[IMathAccent](../../aspose.slides/imathaccent) - New instance of type [IMathAccent](../../aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```
Dessine une barre au-dessus de cet élément

--------------------

> ```
> Exemple :
>  
>  IMathBar bar = new MathematicalText("x").overbar();
>  ```

**Retour :**
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance du type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```
Dessine une barre en dessous de cet élément

--------------------

> ```
> Exemple :
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Place cet élément dans un groupe en utilisant une accolade inférieure

--------------------

> ```
> Exemple :
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retour :**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```
Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre

--------------------

> ```
> Exemple :
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| character | char | Caractère de groupement tel que ACCOLADE INFERIEURE (U+23DF) ou tout autre |
| position | int | Position du caractère de groupement |
| verticalJustification | int | Justification verticale du caractère de groupement. Spécifie l'alignement de l'objet par rapport à la ligne de base. Par exemple, lorsque le caractère de groupement est au-dessus de l'objet, la justification verticale « Top » indique que le haut de l'objet se trouve sur la ligne de base ; lorsque la justification verticale est réglée sur « Bottom », le bas de l'objet est sur la ligne de base. |

**Retour :**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance du type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```
Place cet élément dans une boîte à bordure

--------------------

> ```
> Exemple :
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte à bordure avec cet élément placé à l'intérieur
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```
Place cet élément dans une boîte à bordure

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Masquer le bord supérieur |
| hideBottom | boolean | Masquer le bord inférieur |
| hideLeft | boolean | Masquer le bord gauche |
| hideRight | boolean | Masquer le bord droit |
| strikethroughHorizontal | boolean | Trait horizontal de la boîte à bordure |
| strikethroughVertical | boolean | Trait vertical de la boîte à bordure |
| strikethroughBottomLeftToTopRight | boolean | Trait de la boîte à bordure de bas-gauche à haut-droit |
| strikethroughTopLeftToBottomRight | boolean | Trait de la boîte à bordure de haut-gauche à bas-droit |

**Retour :**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte à bordure avec cet élément placé à l'intérieur
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Place cet élément dans une boîte non visuelle (regroupement logique) qui est utilisée pour regrouper les composants d’une équation ou d’une autre instance de texte mathématique. Un objet encadré peut (par exemple) servir d’émulateur d’opérateur avec ou sans point d’alignement, servir de point de rupture de ligne, ou être groupé de façon à ne pas autoriser les ruptures de ligne à l’intérieur.

--------------------

> ```
> Exemple :
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
>  ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Boîte logique avec cet élément placé à l’intérieur
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()


Obtenir les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)