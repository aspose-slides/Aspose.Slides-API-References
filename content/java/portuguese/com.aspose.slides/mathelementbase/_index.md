---
title: MathElementBase
second_title: Referência da API Aspose.Slides para Java
description: Classe base para IMathElement com a implementação de alguns métodos que são comuns a todas as classes herdadas. Apenas para uso interno.
type: docs
url: /pt/com.aspose.slides/mathelementbase/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Classe base para IMathElement com a implementação de alguns métodos que são comuns a todas as classes herdadas. Para uso interno apenas. A classe herdada deve ser IMathElement.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Retorna o objeto Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Junta um elemento matemático e forma um bloco matemático |
| [join(String mathText)](#join-java.lang.String-) | Junta um texto matemático e forma um bloco matemático |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Cria uma fração com este numerador e denominador especificado |
| [divide(String denominator)](#divide-java.lang.String-) | Cria uma fração com este numerador e denominador especificado |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Cria uma fração do tipo especificado com este numerador e denominador especificado |
| [enclose()](#enclose--) | Envolve um elemento matemático entre parênteses |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Recebe uma função de um argumento usando esta instância como nome da função |
| [function(String functionArgument)](#function-java.lang.String-) | Recebe uma função de um argumento usando esta instância como nome da função |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Recebe a função especificada usando esta instância como argumento |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Recebe a função especificada usando esta instância como argumento |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Recebe a função especificada usando esta instância como argumento |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Recebe a função especificada usando esta instância como argumento e argumento adicional especificado |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Cria subscrito |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Cria subscrito |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Cria sobrescrito |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Cria sobrescrito |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria subscrito e sobrescrito à direita |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Cria subscrito e sobrescrito à direita |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria subscrito e sobrescrito à esquerda |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Cria subscrito e sobrescrito à esquerda |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [radical(String degree)](#radical-java.lang.String-) | Especifica a raiz matemática do grau fornecido a partir do argumento especificado. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Recebe limite superior |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Recebe limite superior |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Recebe limite inferior |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Recebe limite inferior |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Cria um operador N-ário |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Cria um operador N-ário |
| [toMathArray()](#toMathArray--) | Coloca em uma matriz vertical |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Recebe a integral |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Recebe a integral |
| [integral(int integralType)](#integral-int-) | Recebe a integral sem limites |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Recebe a integral |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Recebe a integral |
| [accent(char accentCharacter)](#accent-char-) | Define um acento (um caractere no topo deste elemento) |
| [overbar()](#overbar--) | Define uma barra no topo deste elemento |
| [underbar()](#underbar--) | Define uma barra na base deste elemento |
| [group()](#group--) | Coloca este elemento em um grupo usando uma chave inferior |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Coloca este elemento em um grupo usando um caractere de agrupamento, como chave inferior ou outro |
| [toBorderBox()](#toBorderBox--) | Coloca este elemento em uma caixa de borda |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Coloca este elemento em uma caixa de borda |
| [toBox()](#toBox--) | Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. |
| [getChildren()](#getChildren--) | Obtém elementos filhos |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. IDOMObject somente leitura.

**Retorna:**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Junta um elemento matemático e forma um bloco matemático

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | O elemento a ser juntado |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - Um novo IMathBlock contendo esta instância e argumento especificado

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Junta um texto matemático e forma um bloco matemático

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | Texto matemático a ser juntado |

**Retorna:**
[IMathBlock](../../com.aspose.slides/imathblock) - Um novo IMathBlock contendo esta instância e argumento especificado

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Cria uma fração com este numerador e denominador especificado

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |

**Retorna:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nova fração

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Cria uma fração com este numerador e denominador especificado

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | java.lang.String | Denominador |

**Retorna:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nova fração

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Cria uma fração do tipo especificado com este numerador e denominador especificado

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fração: Bar, NoBar, Skewed, Linear |

**Retorna:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nova fração

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Cria uma fração do tipo especificado com este numerador e denominador especificado

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| denominator | java.lang.String | Denominador |
| fractionType | int | Tipo de fração: Bar, NoBar, Skewed, Linear |

**Retorna:**
[IMathFraction](../../com.aspose.slides/imathfraction) - nova fração

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Envolve um elemento matemático entre parênteses

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que inclui os parênteses

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Envolve um elemento matemático em caracteres especificados, como parênteses ou outros caracteres como moldura

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| beginningCharacter | char | Caractere inicial (geralmente colchete esquerdo) |
| endingCharacter | char | Caractere final (geralmente colchete direito) |

**Retorna:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - O elemento matemático do tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) que inclui os caracteres especificados como moldura

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Recebe uma função de um argumento usando esta instância como nome da função

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Um argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Recebe uma função de um argumento usando esta instância como nome da função

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionArgument | java.lang.String | Um argumento da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Recebe a função especificada usando esta instância como argumento

--------------------

> ```
> Exemplo:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Nome da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Recebe a função especificada usando esta instância como argumento

--------------------

> ```
> Exemplo:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionName | java.lang.String | Nome da função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Recebe a função especificada usando esta instância como argumento

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | int | Um dos tipos de função comuns de um argumento |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Recebe a função especificada usando esta instância como argumento e argumento adicional especificado

--------------------

> ```
> Exemplo:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Retorna o logaritmo de 'x' na base '5'
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | int | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Argumento adicional dependendo do tipo de função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Recebe a função especificada usando esta instância como argumento e argumento adicional especificado

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Retorna o logaritmo de 'x' na base '5'
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| functionType | int | Um dos tipos de função comuns de dois argumentos: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Argumento adicional dependendo do tipo de função |

**Retorna:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Novo elemento matemático do tipo [IMathFunction](../../com.aspose.slides/imathfunction)

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Cria subscrito

--------------------

> ```
> Exemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscrito (índice inferior à direita) |

**Retorna:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Novo elemento matemático do tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Cria subscrito

--------------------

> ```
> Exemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | java.lang.String | Subscrito (índice inferior à direita) |

**Retorna:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Novo elemento matemático do tipo [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Cria sobrescrito

--------------------

> ```
> Exemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Sobrescrito (índice superior à direita) |

**Retorna:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Novo elemento matemático do tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Cria sobrescrito

--------------------

> ```
> Exemplo:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| superscript | java.lang.String | Sobrescrito (índice superior à direita) |

**Retorna:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Novo elemento matemático do tipo [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Cria subscrito e sobrescrito à direita

--------------------

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscrito (índice inferior à direita) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Sobrescrito (índice superior à direita) |

**Retorna:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Cria subscrito e sobrescrito à direita

--------------------
> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | java.lang.String | Subscrito (índice inferior à direita) |
| superscript | java.lang.String | Sobrescrito (índice superior à direita) |

**Retorna:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Novo elemento matemático do tipo [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Cria subscrito e sobrescrito à esquerda

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Subscrito (índice inferior à esquerda) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Sobrescrito (índice superior à esquerda) |

**Retorna:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Novo elemento matemático do tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Cria subscrito e sobrescrito à esquerda

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| subscript | java.lang.String | Subscrito (índice inferior à esquerda) |
| superscript | java.lang.String | Sobrescrito (índice superior à esquerda) |

**Retorna:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Novo elemento matemático do tipo [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argumento do radical |

**Retorna:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nova instância do tipo [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Especifica a raiz matemática do grau fornecido a partir do argumento especificado.

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| degree | java.lang.String | Argumento do radical |

**Retorna:**
[IMathRadical](../../com.aspose.slides/imathradical) - Nova instância do tipo [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Define o limite superior

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nova instância do tipo [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Define o limite superior

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nova instância do tipo [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Define o limite inferior

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nova instância do tipo [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Define o limite inferior

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Retorna:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Nova instância do tipo [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Cria um operador N-ário

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo do operador N-ário |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | O limite inferior |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | O limite superior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Cria um operador N-ário

---

> ```
> Exemplo:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | O tipo do operador N-ário |
| lowerLimit | java.lang.String | O limite inferior |
| upperLimit | java.lang.String | O limite superior |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Coloca em um arranjo vertical

---

> ```
> Exemplo:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Retorna:**
[IMathArray](../../com.aspose.slides/imatharray) - Nova instância do tipo [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Representa a integral

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | int | Tipo da integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior da integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superior da integral |
| limitLocations | int | localização dos limites |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Representa a integral

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | int | Tipo da integral |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite inferior da integral |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Limite superior da integral |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Representa a integral sem limites

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | int | Tipo da integral |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Representa a integral

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | int | Tipo da integral |
| lowerLimit | java.lang.String | Limite inferior da integral |
| upperLimit | java.lang.String | Limite superior da integral |
| limitLocations | int | localização dos limites |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Representa a integral

---

> ```
> Exemplo:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| integralType | int | Tipo da integral |
| lowerLimit | java.lang.String | Limite inferior da integral |
| upperLimit | java.lang.String | Limite superior da integral |

**Retorna:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Nova instância do tipo [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Define um acento (um caractere na parte superior deste elemento)

---

> ```
> Exemplo:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| accentCharacter | char | Caractere de acento. O valor deve estar dentro do intervalo (U+0300\\u2013U+036F) ou (U+20D0\\u2013U+20EF) |

**Retorna:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Nova instância do tipo [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Define uma barra na parte superior deste elemento

---

> ```
> Exemplo:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Retorna:**
[IMathBar](../../com.aspose.slides/imathbar) - Nova instância do tipo [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Define uma barra na parte inferior deste elemento

---

> ```
> Exemplo:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Retorna:**
[IMathBar](../../com.aspose.slides/imathbar) - Nova instância do tipo [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Coloca este elemento em um grupo usando uma chave curvada inferior

---

> ```
> Exemplo:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Retorna:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nova instância do tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Coloca este elemento em um grupo usando um caractere de agrupamento, como uma chave curvada inferior ou outro

---

> ```
> Exemplo:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| character | char | Caractere de agrupamento, como CHAVE CURVADA INFERIOR (U+23DF) ou qualquer outro |
| position | int | Posição do caractere de agrupamento |
| verticalJustification | int | Justificação vertical do caractere de agrupamento. Especifica o alinhamento do objeto em relação à linha de base. Por exemplo, quando o caractere de agrupamento está acima do objeto, VerticalJustification de Top indica que a parte superior do objeto está na linha de base; quando VerticalJustification é definido como Bottom, a parte inferior do objeto está na linha de base |

**Retorna:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Nova instância do tipo [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Coloca este elemento em uma caixa de borda

---

> ```
public final IMathBorderBox toBorderBox()
```

**Retorna:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Caixa de borda com este elemento colocado dentro
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Coloca este elemento em uma caixa de borda

---

> ```
> Exemplo:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hideTop | boolean | Ocultar borda superior |
| hideBottom | boolean | Ocultar borda inferior |
| hideLeft | boolean | Ocultar borda esquerda |
| hideRight | boolean | Ocultar borda direita |
| strikethroughHorizontal | boolean | Tachado horizontal da caixa de borda |
| strikethroughVertical | boolean | Tachado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | boolean | Tachado da caixa de borda de baixo-esquerda para cima-direita |
| strikethroughTopLeftToBottomRight | boolean | Tachado da caixa de borda de cima-esquerda para baixo-direita |

**Retorna:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Caixa de borda com este elemento colocado dentro
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Coloca este elemento em uma caixa não visual (agrupamento lógico) que é usada para agrupar componentes de uma equação ou outra instância de texto matemático. Um objeto em caixa pode (por exemplo) servir como um emulador de operador com ou sem ponto de alinhamento, servir como ponto de quebra de linha ou ser agrupado de modo a não permitir quebras de linha internas.

---

> ```
> Exemplo:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Retorna:**
[IMathBox](../../com.aspose.slides/imathbox) - Caixa lógica com este elemento colocado dentro
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Obtém os elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[] - Array de [IMathElement](../../com.aspose.slides/imathelement)