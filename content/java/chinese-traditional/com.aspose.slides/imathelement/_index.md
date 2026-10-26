---
title: IMathElement
second_title: Aspose.Slides for Java API Reference
description: Base interface of any mathematical element  fraction mathmatical text function expression with multiple elements etc
type: docs
url: /zh-hant/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

任何數學元素的基礎介面：分數、數學文字、函數、包含多個元素的表達式等

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildren()](#getChildren--) | 取得子元素 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 加入一個數學元素並形成數學區塊 |
| [join(String mathText)](#join-java.lang.String-) | 加入數學文字並形成數學區塊 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 以此分子與指定分母建立分數 |
| [divide(String denominator)](#divide-java.lang.String-) | 以此分子與指定分母建立分數 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 以此分子與指定分母建立指定類型的分數 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 以此分子與指定分母建立指定類型的分數 |
| [enclose()](#enclose--) | 將數學元素括於括號中 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 以指定字符（例如括號或其他字符）將此元素框住 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 以此實例作為函數名稱，對一個參數使用函數 |
| [function(String functionArgument)](#function-java.lang.String-) | 以此實例作為函數名稱，對一個參數使用函數 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 以此實例作為參數，使用指定函數 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 以此實例作為參數，使用指定函數 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 以此實例作為參數，使用指定函數 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 以此實例作為參數，使用指定函數並加上指定的額外參數 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 以此實例作為參數，使用指定函數並加上指定的額外參數 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 建立下標 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 建立下標 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 建立上標 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 建立上標 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在左側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 在左側建立下標與上標 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定給定次數的數學根號，以指定參數為底 |
| [radical(String degree)](#radical-java.lang.String-) | 指定給定次數的數學根號，以指定參數為底 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 設定上限 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 設定上限 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 設定下限 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 設定下限 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 N 進制運算子 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | 建立 N 進制運算子 |
| [toMathArray()](#toMathArray--) | 放入垂直陣列 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 取得積分 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 取得積分 |
| [integral(int integralType)](#integral-int-) | 取得無上下限的積分 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 取得無上下限的積分 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 取得無上下限的積分 |
| [accent(char accentCharacter)](#accent-char-) | 設定重音符號（此元素上方的字符） |
| [overbar()](#overbar--) | 在此元素上方設定橫線 |
| [underbar()](#underbar--) | 在此元素下方設定橫線 |
| [group()](#group--) | 使用底部大括號將此元素置於群組中 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 使用分組字符（例如底部大括號或其他）將此元素置於群組中 |
| [toBorderBox()](#toBorderBox--) | 將此元素放入邊框盒中 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 將此元素放入邊框盒中 |
| [toBox()](#toBox--) | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組 |

### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

取得子元素

**回傳值：**
com.aspose.slides.IMathElement[]

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

加入一個數學元素並形成數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要加入的元素 |

**回傳值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例與指定參數的新 IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

加入數學文字並形成數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | java.lang.String | 要加入的數學文字 |

**回傳值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例與指定參數的新 IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

以此分子與指定分母建立分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

以此分子與指定分母建立分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

以此分子與指定分母建立指定類型的分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型：Bar、NoBar、Skewed、Linear |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

以此分子與指定分母建立指定類型的分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |
| fractionType | int | 分數類型：Bar、NoBar、Skewed、Linear |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

將數學元素括於括號中

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**回傳值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含括號

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

以指定字符（例如括號或其他字符）將此元素框住

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常為左括號） |
| endingCharacter | char | 結束字符（通常為右括號） |

**回傳值：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含指定字符作為框架

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

以此實例作為函數名稱，對一個參數使用函數

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 函數的參數 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

以此實例作為函數名稱，對一個參數使用函數

--------------------

> ```
> 範例:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionArgument | java.lang.String | 函數的參數 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

以此實例作為參數，使用指定函數

--------------------

> ```
> 範例:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 函數名稱 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

以此實例作為參數，使用指定函數

--------------------

> ```
> 範例:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | java.lang.String | 函數名稱 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

以此實例作為參數，使用指定函數

--------------------

> ```
> 範例:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 常見單參數函數類型之一 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

以此實例作為參數，使用指定函數並加上指定的額外參數

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 返回以 '5' 為底的 'x' 的對數
```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 兩參數常見函數類型之一：Log、Lim、Min、Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 依函數類型而定的額外參數 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

以此實例作為參數，使用指定函數並加上指定的額外參數

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 返回以 '5' 為底的 'x' 的對數
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 兩參數常見函數類型之一：Log、Lim、Min、Max |
| additionalArgument | java.lang.String | 依函數類型而定的額外參數 |

**回傳值：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 類型為 [IMathFunction](../../com.aspose.slides/imathfunction) 的新數學元素

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```

建立下標

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下標（右側的低位指標） |

**回傳值：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 類型為 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 的新數學元素

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```

建立下標

--------------------

> ```
> 範例:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 下標（右側的低位指標） |

**回傳值：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 類型為 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 的新數學元素

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

建立上標

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上標（右側的高位指標） |

**回傳值：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 類型為 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 的新數學元素

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```

建立上標

--------------------

> ```
> 範例:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | java.lang.String | 上標（右側的高位指標） |

**回傳值：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 類型為 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 的新數學元素

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

在右側建立下標與上標

--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下標（右側的低位指標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上標（右側的高位指標） |

**回傳值：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 類型為 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 的新數學元素

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
在右側建立下標與上標
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下標（右側的下指標） |
| superscript | java.lang.String | 上標（右側的上指標） |

**返回值：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新數學元素類型為 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

在左側建立下標與上標
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下標（左側的下指標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上標（左側的上指標） |

**返回值：**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新數學元素類型為 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

在左側建立下標與上標
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| subscript | java.lang.String | 下標（左側的下指標） |
| superscript | java.lang.String | 上標（左側的上指標） |

**返回值：**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新數學元素類型為 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

指定給定次方的數學根號，來源於指定的參數。
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 根號的次方參數 |

**返回值：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新實例類型為 [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

指定給定次方的數學根號，來源於指定的參數。
--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| degree | java.lang.String | 根號的次方參數 |

**返回值：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新實例類型為 [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

取得上限
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回值：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

取得上限
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**返回值：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

取得下限
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**返回值：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

取得下限
--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**返回值：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

建立 N 元運算子
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | int | N 元運算子的類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

建立 N 元運算子
--------------------

> ```
> 範例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | int | N 元運算子的類型 |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

放入垂直陣列
--------------------

> ```
> 範例:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**返回值：**
[IMathArray](../../com.aspose.slides/imatharray) - 新實例類型為 [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

取得積分
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分的下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分的上限 |
| limitLocations | int | 限制位置 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

取得積分
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分的下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分的上限 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

取得無上下限的積分
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| integralType | int | 積分類型 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

取得積分
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分的下限 |
| upperLimit | java.lang.String | 積分的上限 |
| limitLocations | int | 限制位置 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

取得積分
--------------------

> ```
> 範例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分的下限 |
| upperLimit | java.lang.String | 積分的上限 |

**返回值：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

設定重音標記（此元素上方的字元）
--------------------

> ```
> 範例:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| accentCharacter | char | 重音字元。值應位於 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 |

**返回值：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新實例類型為 [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

在此元素上方設定橫線
--------------------

> ```
> 範例:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新實例類型為 [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

在此元素下方設定橫線
--------------------

> ```
> 範例:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新實例類型為 [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

使用底部大括號將此元素放入群組
--------------------

> ```
> 範例:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**返回值：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新實例類型為 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

使用分組字元（例如底部大括號或其他）將此元素放入群組
--------------------

> ```
> 範例:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| character | char | 分組字元，例如底部大括號 (U+23DF) 或任何其他 |
| position | int | 分組字元的位置 |
| verticalJustification | int | 分組字元的垂直對齊方式。指定物件相對於基線的對齊。例如，當分組字元位於物件上方時，VerticalJustification 為 Top 表示物件的頂部落在基線上；當 VerticalJustification 設為 Bottom 時，物件的底部在基線上 |

**返回值：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新實例類型為 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

將此元素放入邊框盒
--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的邊框盒
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

將此元素放入邊框盒
--------------------

> ```
> 範例:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| hideTop | boolean | 隱藏上緣 |
| hideBottom | boolean | 隱藏下緣 |
| hideLeft | boolean | 隱藏左緣 |
| hideRight | boolean | 隱藏右緣 |
| strikethroughHorizontal | boolean | 水平刪除線 |
| strikethroughVertical | boolean | 垂直刪除線 |
| strikethroughBottomLeftToTopRight | boolean | 從左下到右上刪除線 |
| strikethroughTopLeftToBottomRight | boolean | 從左上到右下刪除線 |

**返回值：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的邊框盒
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀物件可（例如）作為具有或不具有對齊點的運算子模擬器、作為換行點，或被分組以防止內部換行。
--------------------

> ```
> 範例:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**返回值：**
[IMathBox](../../com.aspose.slides/imathbox) - 邏輯盒子，其中包含此元素