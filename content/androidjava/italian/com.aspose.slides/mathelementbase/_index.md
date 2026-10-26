---
title: MathElementBase
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Classe base per IMathElement con l'implementazione di alcuni metodi comuni a tutte le classi ereditate. Solo uso interno.
type: docs
url: /it/com.aspose.slides/mathelementbase/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Classe base per IMathElement con l'implementazione di alcuni metodi comuni a tutte le classi ereditate. Solo uso interno. La classe ereditata deve essere IMathElement.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Restituisce l'oggetto Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Unisce un elemento matematico e forma un blocco matematico |
| [join(String mathText)](#join-java.lang.String-) | Unisce un testo matematico e forma un blocco matematico |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Crea una frazione con questo numeratore e il denominatore specificato |
| [divide(String denominator)](#divide-java.lang.String-) | Crea una frazione con questo numeratore e il denominatore specificato |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [enclose()](#enclose--) | Racchiude un elemento matematico tra parentesi |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri come incorniciatura |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [function(String functionArgument)](#function-java.lang.String-) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Prende la funzione specificata usando questa istanza come argomento |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Prende la funzione specificata usando questa istanza come argomento |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Prende la funzione specificata usando questa istanza come argomento |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Crea un pedice |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Crea un pedice |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Crea un apice |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Crea un apice |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea pedice e apice a destra |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Crea pedice e apice a destra |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea pedice e apice a sinistra |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Crea pedice e apice a sinistra |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [radical(String degree)](#radical-java.lang.String-) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Prende il limite superiore |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Prende il limite superiore |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Prende il limite inferiore |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Prende il limite inferiore |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea un operatore N-ario |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Crea un operatore N-ario |
| [toMathArray()](#toMathArray--) | Inserisce in un array verticale |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Prende l'integrale |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Prende l'integrale |
| [integral(int integralType)](#integral-int-) | Prende l'integrale senza limiti |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Prende l'integrale |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Prende l'integrale |
| [accent(char accentCharacter)](#accent-char-) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [overbar()](#overbar--) | Imposta una barra sopra questo elemento |
| [underbar()](#underbar--) | Imposta una barra sotto questo elemento |
| [group()](#group--) | Colloca questo elemento in un gruppo usando una parentesi graffa inferiore |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento come una parentesi graffa inferiore o un altro |
| [toBorderBox()](#toBorderBox--) | Colloca questo elemento in una casella di bordo |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Colloca questo elemento in una casella di bordo |
| [toBox()](#toBox--) | Colloca questo elemento in una scatola non visiva (raggruppamento logico) utilizzata per raggruppare componenti di un'equazione o altra istanza di testo matematico. |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. IDOMObject sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Unisce un elemento matematico e forma un blocco matematico

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento da unire |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuovo IMathBlock contenente questa istanza e l'argomento specificato

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Unisce un testo matematico e forma un blocco matematico

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | Testo matematico da unire |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuovo IMathBlock contenente questa istanza e l'argomento specificato

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMMathElement denominator)
```

Crea una frazione con questo numeratore e il denominatore specificato

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nuova frazione

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Crea una frazione con questo numeratore e il denominatore specificato

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | java.lang.String | Denominatore |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nuova frazione

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominatore |
| fractionType | int | Tipo di frazione: Bar, NoBar, Skewed, Linear |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nuova frazione

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| denominator | java.lang.String | Denominatore |
| fractionType | int | Tipo di frazione: Bar, NoBar, Skewed, Linear |

**Restituisce:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nuova frazione

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Racchiude un elemento matematico tra parentesi

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) che include le parentesi

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri come incorniciatura

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere iniziale (di solito parentesi sinistra) |
| endingCharacter | char | Carattere finale (di solito parentesi destra) |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) che include i caratteri specificati come incorniciatura

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Prende una funzione di un argomento usando questa istanza come nome della funzione

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Un argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Prende una funzione di un argomento usando questa istanza come nome della funzione

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionArgument | java.lang.String | Un argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Prende la funzione specificata usando questa istanza come argomento

--------------------

> ```
> Esempio:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nome della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Prende la funzione specificata usando questa istanza come argomento

--------------------

> ```
> Esempio:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionName | java.lang.String | Nome della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Prende la funzione specificata usando questa istanza come argomento

--------------------

> ```
> Esempio:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | int | Uno dei tipi di funzione comune a un argomento |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Restituisce il logaritmo di 'x' alla base '5'
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | int | Uno dei tipi di funzione comune a due argomenti: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argomento aggiuntivo a seconda del tipo di funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Restituisce il logaritmo di 'x' alla base '5'
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| functionType | int | Uno dei tipi di funzione comune a due argomenti: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argomento aggiuntivo a seconda del tipo di funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Nuovo elemento matematico di tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Crea un pedice

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Pedice (indice inferiore a destra) |

**Restituisce:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nuovo elemento matematico di tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Crea un pedice

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | java.lang.String | Pedice (indice inferiore a destra) |

**Restituisce:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Nuovo elemento matematico di tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Crea un apice

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Apice (indice superiore a destra) |

**Restituisce:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Crea un apice

--------------------

> ```
> Esempio:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | java.lang.String | Apice (indice superiore a destra) |

**Restituisce:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Crea pedice e apice a destra

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Pedice (indice inferiore a destra) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Apice (indice superiore a destra) |

**Restituisce:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nuovo elemento matematico di tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Crea pedice e apice a destra

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | java.lang.String | Pedice (indice inferiore a destra) |
| superscript | java.lang.String | Apice (indice superiore a destra) |

**Restituisce:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Nuovo elemento matematico di tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Crea pedice e apice a sinistra

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Pedice (indice inferiore a sinistra) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Apice (indice superiore a sinistra) |

**Restituisce:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nuovo elemento matematico di tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Crea pedice e apice a sinistra

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | java.lang.String | Pedice (indice inferiore a sinistra) |
| superscript | java.lang.String | Apice (indice superiore a sinistra) |

**Restituisce:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Nuovo elemento matematico di tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Specifica la radice matematica del grado dato dall'argomento specificato.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argomento del radicale |

**Restituisce:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nuova istanza di tipo [IMathRadical](../../com.aspose.slides/imathradical)

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Specifica la radice matematica del grado dato dall'argomento specificato.

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | java.lang.String | Argomento del radicale |

**Restituisce:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nuova istanza di tipo [IMathRadical](../../com.aspose.slides/imathradical)

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Prende il limite superiore

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nuova istanza di tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Prende il limite superiore

--------------------

> ```
public final IMathLimit setUpperLimit(String limit)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limit | java.lang.String | limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nuova istanza di tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Prende il limite inferiore

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nuova istanza di tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Prende il limite inferiore

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| limit | java.lang.String | limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nuova istanza di tipo [IMathLimit](../../com.aspose.slides/imathlimit)

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Crea un operatore N-ario

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di operatore N-ario |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Il limite inferiore |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Il limite superiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Crea un operatore N-ario

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di operatore N-ario |
| lowerLimit | java.lang.String | Il limite inferiore |
| upperLimit | java.lang.String | Il limite superiore |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Inserisce in un array verticale

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Restituisce:**
[IMathArray](../../com.aspose.slides/imatharray) - Nuova istanza di tipo [IMathArray](../../com.aspose.slides/imatharray)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Prende l'integrale

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | int | Tipo di integrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore dell'integrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superiore dell'integrale |
| limitLocations | int | Posizione dei limiti |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Prende l'integrale

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | int | Tipo di integrale |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferiore dell'integrale |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superiore dell'integrale |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Prende l'integrale senza limiti

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | int | Tipo di integrale |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Prende l'integrale

--------------------

> ```
> Esempio:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | int | Tipo di integrale |
| lowerLimit | java.lang.String | Limite inferiore dell'integrale |
| upperLimit | java.lang.String | Limite superiore dell'integrale |
| limitLocations | int | Posizione dei limiti |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Prende l'integrale

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | int | Tipo di integrale |
| lowerLimit | java.lang.String | Limite inferiore dell'integrale |
| upperLimit | java.lang.String | Limite superiore dell'integrale |

**Restituisce:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nuova istanza di tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Imposta un segno di accento (un carattere sopra questo elemento)

--------------------

> ```
> Esempio:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| accentCharacter | char | Carattere di accento. Il valore deve rientrare nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) |

**Restituisce:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nuova istanza di tipo [IMathAccent](../../com.aspose.slides/imathaccent)

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Imposta una barra sopra questo elemento

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Restituisce:**
[IMathBar](../../com.aspose.slides/imathbar) - Nuova istanza di tipo [IMathBar](../../com.aspose.slides/imathbar)

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Imposta una barra sotto questo elemento

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Restituisce:**
[IMathBar](../../com.aspose.slides/imathbar) - Nuova istanza di tipo [IMathBar](../../com.aspose.slides/imathbar)

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Colloca questo elemento in un gruppo usando una parentesi graffa inferiore

--------------------

> ```
> Esempio:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```


**Restituisce:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nuova istanza di tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Colloca questo elemento in un gruppo usando un carattere di raggruppamento come una parentesi graffa inferiore o un altro

--------------------

> ```
> Esempio:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| character | char | Carattere di raggruppamento come PARENTESI GRAFFA INFERIORE (U+23DF) o qualsiasi altro |
| position | int | Posizione del carattere di raggruppamento |
| verticalJustification | int | Allineamento verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea di base; quando VerticalJustification è impostato a Bottom, la parte inferiore dell'oggetto è sulla linea di base |

**Restituisce:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nuova istanza di tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)

### toBorderBox() {#toBorderBox--}
```
public



```

Colloca questo elemento in una casella di bordo

--------------------

> ```
> Esempio:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Casella di bordo con questo elemento inserito all'interno

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Colloca questo elemento in una casella di bordo

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Barrato orizzontale della casella di bordo |
| strikethroughVertical | boolean | Barrato verticale della casella di bordo |
| strikethroughBottomLeftToTopRight | boolean | Barrato diagonale da basso-sinistra a alto-destra |
| strikethroughTopLeftToBottomRight | boolean | Barrato diagonale da alto-sinistra a basso-destra |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Casella di bordo con questo elemento inserito all'interno

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Colloca questo elemento in una scatola non visiva (raggruppamento logico) che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico. Un oggetto incorniciato può (ad esempio) servire come emulatore di operatore con o senza punto di allineamento, servire come punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Restituisce:**
[IMathBox](../../com.aspose.slides/imathbox) - Scatola logica con questo elemento inserito all'interno

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[] - Array di [IMathElement](../../com.aspose.slides/imathelement)