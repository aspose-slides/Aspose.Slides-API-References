---  
title: IMathElement  
second_title: Aspose.Slides for Java API 参考  
description: 任何数学元素的基础接口，包括分数、数学文本、函数、含有多个元素的表达式等  
type: docs  
url: /zh/com.aspose.slides/imathelement/  
---```
public interface IMathElement
```

任何数学元素的基础接口：分数、数学文本、函数、包含多个元素的表达式等  

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildren()](#getChildren--) | 获取子元素 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 连接一个数学元素并形成数学块 |
| [join(String mathText)](#join-java.lang.String-) | 连接一个数学文本并形成数学块 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 使用此分子和指定分母创建分数 |
| [divide(String denominator)](#divide-java.lang.String-) | 使用此分子和指定分母创建分数 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 使用此分子和指定分母创建指定类型的分数 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 使用此分子和指定分母创建指定类型的分数 |
| [enclose()](#enclose--) | 用括号包裹数学元素 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用括号或其他字符将此元素包裹为框架 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 将此实例作为函数名，接受一个参数的函数 |
| [function(String functionArgument)](#function-java.lang.String-) | 将此实例作为函数名，接受一个参数的函数 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 将此实例作为参数，接受指定函数 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 将此实例作为参数，接受指定函数 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 将此实例作为参数，接受指定函数 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 将此实例作为参数，接受指定函数并附加额外参数 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 将此实例作为参数，接受指定函数并附加额外参数 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 创建下标 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 创建下标 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 创建上标 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 创建上标 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在右侧创建下标和上标 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 在右侧创建下标和上标 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在左侧创建下标和上标 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 在左侧创建下标和上标 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定给定次数的数学根 |
| [radical(String degree)](#radical-java.lang.String-) | 指定给定次数的数学根 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 取上限 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 取上限 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 取下限 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 取下限 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建 N 元运算符 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | 创建 N 元运算符 |
| [toMathArray()](#toMathArray--) | 放入垂直阵列 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 取积分 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 取积分 |
| [integral(int integralType)](#integral-int-) | 取无上下限的积分 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 取积分 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 取积分 |
| [accent(char accentCharacter)](#accent-char-) | 设置重音标记（元素上方的字符） |
| [overbar()](#overbar--) | 在元素上方设置横线 |
| [underbar()](#underbar--) | 在元素下方设置横线 |
| [group()](#group--) | 使用底部大括号将此元素放入组中 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 使用分组字符（如底部大括号等）将此元素放入组中 |
| [toBorderBox()](#toBorderBox--) | 将此元素放入边框盒中 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 将此元素放入边框盒中 |
| [toBox()](#toBox--) | 将此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本实例的组件进行分组 |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

获取子元素

**返回:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

连接一个数学元素并形成数学块

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要连接的元素 |

**返回:**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此实例和指定参数的新 IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

连接一个数学文本并形成数学块

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 要连接的数学文本 |

**返回:**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此实例和指定参数的新 IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

使用此分子和指定分母创建分数

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**返回:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分数
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

使用此分子和指定分母创建分数

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |

**返回:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分数
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

使用此分子和指定分母创建指定类型的分数

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数类型：Bar, NoBar, Skewed, Linear |

**返回:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分数
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

使用此分子和指定分母创建指定类型的分数

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |
| fractionType | int | 分数类型：Bar, NoBar, Skewed, Linear |

**返回:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分数
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

用括号包裹数学元素

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**返回:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含括号的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 类型数学元素
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定字符（如括号或其他字符）将此元素框定

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常为左括号） |
| endingCharacter | char | 结束字符（通常为右括号） |

**返回:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含指定字符框架的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 类型数学元素
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

将此实例作为函数名，接受一个参数的函数

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 函数的参数 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

将此实例作为函数名，接受一个参数的函数

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | java.lang.String | 函数的参数 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

将此实例作为参数，接受指定函数

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 函数名 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

将此实例作为参数，接受指定函数

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionName | java.lang.String | 函数名 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

将此实例作为参数，接受指定函数

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | int | 常见单参函数类型之一 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

将此实例作为参数，接受指定函数并附加额外参数

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 返回 'x' 以 '5' 为底的对数
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | int | 常见双参函数类型之一：Log、Lim、Min、Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 根据函数类型决定的额外参数 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

将此实例作为参数，接受指定函数并附加额外参数

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 返回 'x' 以 '5' 为底的对数
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionType | int | 常见双参函数类型之一：Log、Lim、Min、Max |
| additionalArgument | java.lang.String | 根据函数类型决定的额外参数 |

**返回:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 类型数学元素
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

创建下标

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下标（右侧的下标） |

**返回:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 类型数学元素
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

创建下标

--------------------

> ```
> 示例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下标（右侧的下标） |

**返回:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 类型数学元素
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

创建上标

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上标（右侧的上标） |

**返回:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 类型数学元素
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

创建上标

--------------------

> ```
> 示例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| superscript | java.lang.String | 上标（右侧的上标） |

**返回:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 类型数学元素
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下标（右侧的下标） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上标（右侧的上标） |

**返回:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新的 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 类型数学元素
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
在右侧创建下标和上标

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下标（右侧的下标） |
| superscript | java.lang.String | 上标（右侧的上标） |

**返回:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 类型为 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 的新数学元素
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


在左侧创建下标和上标

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下标（左侧的下标） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上标（左侧的上标） |

**返回:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 类型为 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 的新数学元素
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


在左侧创建下标和上标

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下标（左侧的下标） |
| superscript | java.lang.String | 上标（左侧的上标） |

**返回:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 类型为 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 的新数学元素
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


指定给定指数的数学根

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 根的指数参数 |

**返回:**
[IMathRadical](../../com.aspose.slides/imathradical) - 类型为 [IMathRadical](../../com.aspose.slides/imathradical) 的新实例
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


指定给定指数的数学根

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| degree | java.lang.String | 根的指数参数 |

**返回:**
[IMathRadical](../../com.aspose.slides/imathradical) - 类型为 [IMathRadical](../../com.aspose.slides/imathradical) 的新实例
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


获取上限

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 类型为 [IMathLimit](../../com.aspose.slides/imathlimit) 的新实例
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


获取上限

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | java.lang.String | 上限 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 类型为 [IMathLimit](../../com.aspose.slides/imathlimit) 的新实例
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


获取下限

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 类型为 [IMathLimit](../../com.aspose.slides/imathlimit) 的新实例
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


获取下限

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**返回:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 类型为 [IMathLimit](../../com.aspose.slides/imathlimit) 的新实例
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
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
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


创建 N 元运算符

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | N 元运算符类型 |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


放入垂直数组

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
```

**返回:**
[IMathArray](../../com.aspose.slides/imatharray) - 类型为 [IMathArray](../../com.aspose.slides/imatharray) 的新实例
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分上限 |
| limitLocations | int | 限制位置 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


获取积分

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 积分上限 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


获取无上下限的积分

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | java.lang.String | 积分下限 |
| upperLimit | java.lang.String | 积分上限 |
| limitLocations | int | 限制位置 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


获取积分

--------------------

> ```
> 示例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | int | 积分类型 |
| lowerLimit | java.lang.String | 积分下限 |
| upperLimit | java.lang.String | 积分上限 |

**返回:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 类型为 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 的新实例
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


设置重音符号（此元素顶部的字符）

--------------------

> ```
> 示例：
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| accentCharacter | char | 重音字符。取值应在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 范围内 |

**返回:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 类型为 [IMathAccent](../../com.aspose.slides/imathaccent) 的新实例
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


在此元素顶部设置横线

--------------------

> ```
> 示例：
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**返回:**
[IMathBar](../../com.aspose.slides/imathbar) - 类型为 [IMathBar](../../com.aspose.slides/imathbar) 的新实例
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


在此元素底部设置横线

--------------------

> ```
> 示例：
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**返回:**
[IMathBar](../../com.aspose.slides/imathbar) - 类型为 [IMathBar](../../com.aspose.slides/imathbar) 的新实例
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


使用底部花括号把此元素放入组

--------------------

> ```
> 示例：
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**返回:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 类型为 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 的新实例
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


使用分组字符（如底部花括号或其他）把此元素放入组

--------------------

> ```
> 示例：
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| character | char | 分组字符，例如底部花括号 (U+23DF) 或其他 |
| position | int | 分组字符的位置 |
| verticalJustification | int | 分组字符的垂直对齐方式。指定对象相对于基线的对齐方式。例如，当分组字符位于对象上方时，VerticalJustification 为 Top 表示对象的顶部在基线上；当设置为 Bottom 时，对象的底部在基线上 |

**返回:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 类型为 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 的新实例
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


把此元素放入边框盒

--------------------

> ```
> 示例：
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**返回:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的边框盒
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


把此元素放入边框盒

--------------------

> ```
> 示例：
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hideTop | boolean | 隐藏顶部边缘 |
| hideBottom | boolean | 隐藏底部边缘 |
| hideLeft | boolean | 隐藏左侧边缘 |
| hideRight | boolean | 隐藏右侧边缘 |
| strikethroughHorizontal | boolean | 边框盒水平删除线 |
| strikethroughVertical | boolean | 边框盒垂直删除线 |
| strikethroughBottomLeftToTopRight | boolean | 边框盒左下至右上删除线 |
| strikethroughTopLeftToBottomRight | boolean | 边框盒左上至右下删除线 |

**返回:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的边框盒
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


把此元素放入非可视盒（逻辑分组），用于对方程或其他数学文本实例的组件进行分组。盒装对象可以（例如）充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以防止在内部出现换行。

--------------------

> ```
> 示例：
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**返回:**
[IMathBox](../../com.aspose.slides/imathbox) - 包含此元素的逻辑盒