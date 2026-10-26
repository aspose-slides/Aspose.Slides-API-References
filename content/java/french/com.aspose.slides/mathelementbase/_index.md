---
title: MathElementBase
second_title: Référence de l'API Aspose.Slides pour Java
description: Classe de base pour IMathElement avec l'implémentation de certaines méthodes communes à toutes les classes dérivées. À usage interne uniquement.
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

Classe de base pour IMathElement avec l'implémentation de certaines méthodes communes à toutes les classes héritées. Pour un usage interne uniquement. La classe héritée doit être IMathElement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Retourne l'objet Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joint un élément mathématique et forme un bloc mathématique |
| [join(String mathText)](#join-java.lang.String-) | Joint un texte mathématique et forme un bloc mathématique |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [divide(String denominator)](#divide-java.lang.String-) | Crée une fraction avec ce numérateur et le dénominateur spécifié |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié |
| [enclose()](#enclose--) | Encadre un élément mathématique entre parenthèses |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encadre un élément mathématique avec les caractères spécifiés tels que des parenthèses ou d’autres caractères comme encadrement |
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
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée un indice et un exposant à droite |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Crée un indice et un exposant à droite |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crée un indice et un exposant à gauche |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Crée un indice et un exposant à gauche |
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
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Prend l'intégrale sans limites |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Prend l'intégrale sans limites |
| [accent(char accentCharacter)](#accent-char-) | Définit un accent (un caractère au-dessus de cet élément) |
| [overbar()](#overbar--) | Définit une barre au-dessus de cet élément |
| [underbar()](#underbar--) | Définit une barre en dessous de cet élément |
| [group()](#group--) | Place cet élément dans un groupe en utilisant une accolade inférieure |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Place cet élément dans un groupe en utilisant un caractère de regroupement tel qu'une accolade inférieure ou autre |
| [toBorderBox()](#toBorderBox--) | Place cet élément dans une boîte à bordure |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Place cet élément dans une boîte à bordure |
| [toBox()](#toBox--) | Place cet élément dans une boîte non visuelle (groupement logique) utilisée pour regrouper les composants d'une équation ou d'une autre instance de texte mathématique. |
| [getChildren()](#getChildren--) | Obtient les éléments enfants |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retourne l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retourne :**
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'élément à joindre |

**Retourne :**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nouveau IMathBlock contenant cette instance et l'argument spécifié

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Joint un texte mathématique et forme un bloc mathématique

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Texte mathématique à joindre |

**Retourne :**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nouveau IMathBlock contenant cette instance et l'argument spécifié

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Crée une fraction avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |

**Retourne :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Crée une fraction avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Dénominateur |

**Retourne :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Retourne :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Dénominateur |
| fractionType | int | Type de fraction : Bar, NoBar, Skewed, Linear |

**Retourne :**
[IMathFraction](../../com.aspose.slides/imathfraction) - nouvelle fraction

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Encadre un élément mathématique entre parenthèses

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**Retourne :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les parenthèses

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encadre un élément mathématique avec les caractères spécifiés tels que des parenthèses ou d’autres caractères comme encadrement

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Caractère de début (généralement une accolade gauche) |
| endingCharacter | char | Caractère de fin (généralement une accolade droite) |

**Retourne :**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'élément mathématique de type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) qui inclut les caractères spécifiés comme encadrement

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Un argument de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Prend une fonction d'un argument en utilisant cette instance comme nom de fonction

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | Un argument de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nom de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionName | java.lang.String | Nom de la fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Prend la fonction spécifiée en utilisant cette instance comme argument

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | L'un des types de fonction courants à un argument |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Renvoie le logarithme de 'x' à la base '5'
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | L'un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argument supplémentaire selon le type de fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Prend la fonction spécifiée en utilisant cette instance comme argument et un argument supplémentaire spécifié

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Renvoie le logarithme de 'x' à la base '5'
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| functionType | int | L'un des types de fonction courants à deux arguments : Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argument supplémentaire selon le type de fonction |

**Retourne :**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nouvel élément mathématique de type [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crée un indice

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |

**Retourne :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Crée un indice

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Indice (indice inférieur à droite) |

**Retourne :**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nouvel élément mathématique de type [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Crée un exposant

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Retourne :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouvel élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Crée un exposant

--------------------

> ```
> Exemple:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Exposant (indice supérieur à droite) |

**Retourne :**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nouvel élément mathématique de type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Crée un indice et un exposant à droite

--------------------

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Indice (indice inférieur à droite) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Exposant (indice supérieur à droite) |

**Retourne :**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Crée un indice et un exposant à droite
> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the right) |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Retour:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Crée un indice et un exposant à gauche

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscript (lower index on the left) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Superscript (upper index on the left) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nouvel élément mathématique de type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Crée un indice et un exposant à gauche

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | Subscript (lower index on the left) |
| superscript | java.lang.String | Superscript (upper index on the left) |

**Retour:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nouvel élément mathématique de type [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvel élément mathématique de type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | Argument of Radical |

**Retour:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nouvelle instance de type [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Prend la limite supérieure

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance de type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Prend la limite supérieure

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance de type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Prend la limite inférieure

---

> ```
public final IMathLimit setLowerLimit(IMathElement limit)
```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance de type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Prend la limite inférieure

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retour:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nouvelle instance de type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Crée un opérateur N-aire

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | The lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | The upper limit |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Crée un opérateur N-aire

---

> ```
> Exemple:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Place dans un tableau vertical

---

> ```
> Exemple:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Retour:**
[IMathArray](../../com.aspose.slides/imatharray) - Nouvelle instance de type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Prend l'intégrale

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |
| limitLocations | int | location of limits |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Prend l'intégrale

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit of integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit of integral |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Prend l'intégrale sans limites

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Prend l'intégrale

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |
| limitLocations | int | location of limits |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Prend l'intégrale

---

> ```
> Exemple:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | Integral type |
| lowerLimit | java.lang.String | Lower limit of integral |
| upperLimit | java.lang.String | Upper limit of integral |

**Retour:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nouvelle instance de type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Définit une marque d'accent (un caractère au sommet de cet élément)

---

> ```
> Exemple:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | Accent character. The value should be within the range of (U+0300\\u2013U+036F) or (U+20D0\\u2013U+20EF) |

**Retour:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nouvelle instance de type [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Définit une barre au sommet de cet élément

---

> ```
> Exemple:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance de type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Définit une barre en bas de cet élément

---

> ```
> Exemple:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Retour:**
[IMathBar](../../com.aspose.slides/imathbar) - Nouvelle instance de type [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Place cet élément dans un groupe en utilisant une accolade inférieure

---

> ```
> Exemple:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance de type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Place cet élément dans un groupe en utilisant un caractère de groupement tel qu'une accolade inférieure ou autre

---

> ```
> Exemple:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | int | Position of grouping character |
| verticalJustification | int | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

**Retour:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nouvelle instance de type [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Place cet élément dans une boîte de bordure

---

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte de bordure avec cet élément placé à l'intérieur
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Place cet élément dans une boîte de bordure

---

> ```
> Exemple:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Border Box Strikethrough Horizontal |
| strikethroughVertical | boolean | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Border Box Strikethrough Top-Left to Bottom-Right |

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Boîte de bordure avec cet élément placé à l'intérieur
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Place cet élément dans une boîte non visuelle (groupement logique) qui est utilisée pour regrouper les composants d'une équation ou d'un autre texte mathématique. Un objet encadré peut (par exemple) servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être groupé de manière à ne pas autoriser de ruptures de ligne à l'intérieur.

---

> ```
> Exemple:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Retour:**
[IMathBox](../../com.aspose.slides/imathbox) - Boîte logique avec cet élément placé à l'intérieur
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Retour:**
com.aspose.slides.IMathElement[] - Tableau de [IMathElement](../../com.aspose.slides/imathelement)