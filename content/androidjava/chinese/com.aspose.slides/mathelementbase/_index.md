---
title: MathElementBase
second_title: Aspose.Slides for Android 的 Java API 参考
description: IMathElement 的基类，实现了一些对所有派生类通用的方法，仅供内部使用。
type: docs
url: /zh/com.aspose.slides/mathelementbase/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

IMathElement 的基类，实现了一些对所有派生类通用的方法，仅供内部使用。派生类必须是 IMathElement。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | 返回 Parent_Immediate 对象。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 将数学元素连接并形成数学块 |
| [join(String mathText)](#join-java.lang.String-) | 将数学文本连接并形成数学块 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 使用此分子和指定的分母创建分数 |
| [divide(String denominator)](#divide-java.lang.String-) | 使用此分子和指定的分母创建分数 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 使用此分子和指定的分母创建指定类型的分数 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 使用此分子和指定的分母创建指定类型的分数 |
| [enclose()](#enclose--) | 用括号将数学元素括起来 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 用指定字符（如括号或其他字符）将数学元素框住 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 使用此实例作为函数名，获取参数的函数 |
| [function(String functionArgument)](#function-java.lang.String-) | 使用此实例作为函数名，获取参数的函数 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 使用此实例作为参数，获取指定函数 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 使用此实例作为参数，获取指定函数 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 使用此实例作为参数，获取指定函数 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 使用此实例作为参数，并使用指定的附加参数，获取指定函数 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 使用此实例作为参数，并使用指定的附加参数，获取指定函数 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 创建下标 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 创建下标 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 创建上标 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 创建上标 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在右侧创建下标和上标 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 在右侧创建下标和上标 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在左侧创建下标和上标 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 在左侧创建下标和上标 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定给定次数的数学根号，基于指定的参数。 |
| [radical(String degree)](#radical-java.lang.String-) | 指定给定次数的数学根号，基于指定的参数。 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 获取上限 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 获取上限 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 获取下限 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 获取下限 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建 N 元运算符 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | 创建 N 元运算符 |
| [toMathArray()](#toMathArray--) | 放入垂直数组 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 获取积分 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 获取积分 |
| [integral(int integralType)](#integral-int-) | 获取无上下限的积分 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 获取积分 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 获取积分 |
| [accent(char accentCharacter)](#accent-char-) | 设置重音标记（此元素顶部的字符） |
| [overbar()](#overbar--) | 在此元素顶部设置横线 |
| [underbar()](#underbar--) | 在此元素底部设置横线 |
| [group()](#group--) | 使用底部花括号将此元素放入组中 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 使用分组字符（如底部花括号或其他）将此元素放入组中 |
| [toBorderBox()](#toBorderBox--) | 将此元素放入边框盒 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 将此元素放入边框盒 |
| [toBox()](#toBox--) | 将此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本实例的组件进行分组。 |
| [getChildren()](#getChildren--) | 获取子元素 |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


将数学元素连接并形成数学块

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

Joins a mathematical text and forms a mathematical block

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Mathematical text to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
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
> ```

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

Creates a fraction with this numerator and specified denominator

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | java.lang.String | Denominator |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - new fraction
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

使用此分子和指定的分母创建指定类型的分数

--------------------

> ```
> 示例：
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数类型：Bar, NoBar, Skewed, Linear |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新分数
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
> ```

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
> ```

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes the parenthesis
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Encloses a math element in specified characters such as parenthesis or another characters as framing

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Takes a function of an argument using this instance as the function name

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | An argument of the function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

使用此实例作为函数名，对参数进行函数调用

--------------------

> ```
> 示例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | java.lang.String | 函数的参数 |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新建的类型为 [IMathFunction](../../com.aspose.slides/imathfunction) 的数学元素
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

使用此实例作为参数，获取指定函数

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 函数名称 |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新建的类型为 [IMathFunction](../../com.aspose.slides/imathfunction) 的数学元素
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
> ```

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

使用此实例作为参数，获取指定函数

--------------------

> ```
> 示例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | int | 单参数常用函数类型之一 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 类型为 [IMathFunction](../../com.aspose.slides/imathfunction) 的新数学元素
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Takes specified function using this instance as the argument and specified additional argument

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 返回以 '5' 为底的 'x' 的对数
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Additional argument depending on the type of function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

使用此实例作为参数，获取指定函数并指定附加参数

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 返回以 '5' 为底的 'x' 的对数
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| functionType | int | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Additional argument depending on the type of function |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - New math element of type [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Creates subscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下标（右侧的下标） |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 类型为 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 的新数学元素
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
``` 

创建下标

--------------------

> ```
> 示例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subscript | java.lang.String | 下标（右侧的下标） |

**Returns:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 类型为 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 的新数学元素
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Creates superscript

--------------------

> ```
> 示例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上标（右侧的上标） |

**返回：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 类型为 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 的新数学元素
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```


Creates superscript

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| superscript | java.lang.String | Superscript (upper index on the right) |

**Returns:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - New math element of type [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


在右侧创建下标和上标

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下标（右侧的下标） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上标（右侧的上标） |

**返回：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新建的类型为 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 的数学元素
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

在右侧创建下标和上标

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下标（右侧的下标） |
| superscript | java.lang.String | 上标（右侧的上标） |

**返回：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 类型为 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 的新数学元素
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Creates subscript and superscript on the left

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

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

指定给定次数的数学根号，基于指定的参数。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Argument of Radical |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - New instance of type [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

指定给定次数的数学根号，基于指定的参数。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| degree | java.lang.String | 根号的参数 |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - 类型为 [IMathRadical](../../com.aspose.slides/imathradical) 的新实例
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```


Takes upper limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```


Takes upper limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Takes lower limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Takes lower limit

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| limit | java.lang.String | limit |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - New instance of type [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```
创建 N 元运算符

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | N 元运算符类型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新实例，类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```
创建 N 元运算符

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The N-ary operator type |
| lowerLimit | java.lang.String | The lower limit |
| upperLimit | java.lang.String | The upper limit |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


Puts in a vertical array

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分的下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分的上限 |
| limitLocations | int | 上下限位置 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分的下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分的上限 |

**返回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

获取无上下限的积分

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 积分类型 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | java.lang.String | 积分的下限 |
| upperLimit | java.lang.String | 积分的上限 |
| limitLocations | int | 上下限位置 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | java.lang.String | 积分的下限 |
| upperLimit | java.lang.String | 积分的上限 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - New instance of type [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

设置重音标记（此元素顶部的字符）

--------------------

> ```
> 示例：
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char | 重音字符。取值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新实例，类型为 [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```


Sets a bar on the top of this element

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - New instance of type [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```
设置此元素底部的横线

--------------------

> ```
> 示例：
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**返回：**
[IMathBar](../../com.aspose.slides/imathbar) - 类型为 [IMathBar](../../com.aspose.slides/imathbar) 的新实例
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

使用底部花括号将此元素放入组中

--------------------

> ```
> 示例：
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**返回：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 类型为 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 的新实例
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

使用分组字符（如底部花括号或其他字符）将此元素放入组中

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| character | char | 分组字符，例如底部花括号 (U+23DF) 或其他任意字符 |
| position | int | 分组字符的位置 |
| verticalJustification | int | 分组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部位于基线上；当 VerticalJustification 设置为 Bottom 时，对象的底部位于基线上 |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 类型为 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 的新实例
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

将此元素放入边框盒

--------------------

> ```
> 示例：
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 将此元素放入其中的边框盒
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

将此元素放入边框盒

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hideTop | boolean | 隐藏上边缘 |
| hideBottom | boolean | 隐藏下边缘 |
| hideLeft | boolean | 隐藏左边缘 |
| hideRight | boolean | 隐藏右边缘 |
| strikethroughHorizontal | boolean | 边框盒水平划线 |
| strikethroughVertical | boolean | 边框盒垂直划线 |
| strikethroughBottomLeftToTopRight | boolean | 边框盒从左下到右上划线 |
| strikethroughTopLeftToBottomRight | boolean | 边框盒从左上到右下划线 |

**返回:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的边框盒
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Places this element in a non-visual box (logical grouping) which is used to group components of an equation or other instance of mathematical text. A boxed object can (for example) serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - Logical box with this element placed inside
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()


获取子元素

**返回：**
com.aspose.slides.IMathElement[] - Array of [IMathElement](../../com.aspose.slides/imathelement)