---
title: MathElementBase
second_title: Aspose.Slides for Android 之 Java API 參考
description: IMathElement 的基底類別，實作了一些對所有衍生類別通用的方法。僅供內部使用。
type: docs
url: /zh-hant/com.aspose.slides/mathelementbase/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

IMathElement 的基底類別，實作了一些對所有衍生類別通用的方法。僅供內部使用。繼承類別必須是 IMathElement。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | 傳回 Parent_Immediate 物件。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 將數學元素加入並形成數學區塊 |
| [join(String mathText)](#join-java.lang.String-) | 將數學文字加入並形成數學區塊 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 使用此分子和指定的分母建立分數 |
| [divide(String denominator)](#divide-java.lang.String-) | 使用此分子和指定的分母建立分數 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 使用此分子和指定的分母建立指定類型的分數 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 使用此分子和指定的分母建立指定類型的分數 |
| [enclose()](#enclose--) | 將數學元素以括號括起 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用指定的字元（如括號或其他字元）將數學元素作為框架括起 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 以此實例作為函式名稱，取得參數的函式 |
| [function(String functionArgument)](#function-java.lang.String-) | 以此實例作為函式名稱，取得參數的函式 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 使用此實例作為參數，取得指定的函式 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 使用此實例作為參數，取得指定的函式 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 使用此實例作為參數，取得指定的函式 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 使用此實例作為參數，並加上指定的額外參數，取得指定的函式 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 使用此實例作為參數，並加上指定的額外參數，取得指定的函式 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 建立下標 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 建立下標 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 建立上標 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 建立上標 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在左側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 在左側建立下標與上標 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定從給定參數取得指定次方的數學根號 |
| [radical(String degree)](#radical-java.lang.String-) | 指定從給定參數取得指定次方的數學根號 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 取得上限 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 取得上限 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 取得下限 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 取得下限 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立 N 元運算子 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | 建立 N 元運算子 |
| [toMathArray()](#toMathArray--) | 放入垂直陣列 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 取得積分 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 取得積分 |
| [integral(int integralType)](#integral-int-) | 取得無上下限的積分 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 取得積分 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 取得積分 |
| [accent(char accentCharacter)](#accent-char-) | 設定音調符號（此元素上方的字元） |
| [overbar()](#overbar--) | 在此元素上方設定橫線 |
| [underbar()](#underbar--) | 在此元素下方設定橫線 |
| [group()](#group--) | 使用底部大括號將此元素放入群組 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 使用分組字元（如底部大括號或其他）將此元素放入群組 |
| [toBorderBox()](#toBorderBox--) | 將此元素放入邊框盒 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 將此元素放入邊框盒 |
| [toBox()](#toBox--) | 將此元素放入非視覺盒（邏輯分組），用於將方程式或其他數學文字的組件分組。 |
| [getChildren()](#getChildren--) | 取得子元素 |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

將數學元素加入並形成數學區塊

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

**傳回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例和指定參數的新 IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

將數學文字加入並形成數學區塊

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

**傳回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例和指定參數的新 IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

使用此分子和指定的分母建立分數

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

**傳回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

使用此分子和指定的分母建立分數

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

**傳回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

使用此分子和指定的分母建立指定類型的分數

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

**傳回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

使用此分子和指定的分母建立指定類型的分數

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

**傳回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

將數學元素以括號括起

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**傳回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含括號的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 類型數學元素

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定的字元（如括號或其他字元）將數學元素作為框架括起

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 起始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |

**傳回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含指定字元作為框架的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 類型數學元素

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

以此實例作為函式名稱，取得參數的函式

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
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 函式的參數 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

以此實例作為函式名稱，取得參數的函式

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionArgument | java.lang.String | 函式的參數 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

使用此實例作為參數，取得指定的函式

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 函式名稱 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

使用此實例作為參數，取得指定的函式

> ```
> 範例：
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | java.lang.String | 函式名稱 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

使用此實例作為參數，取得指定的函式

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 單參數常用函式類型之一 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

使用此實例作為參數，並加上指定的額外參數，取得指定的函式

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 返回 'x' 的以 '5' 為底的對數
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 兩參數常用函式類型之一：Log、Lim、Min、Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 依函式類型而定的額外參數 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

使用此實例作為參數，並加上指定的額外參數，取得指定的函式

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 返回 'x' 的以 '5' 為底的對數
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 兩參數常用函式類型之一：Log、Lim、Min、Max |
| additionalArgument | java.lang.String | 依函式類型而定的額外參數 |

**傳回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型數學元素

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

建立下標

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的下標（下標） |

**傳回：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 類型數學元素

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

建立下標

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 右側的下標（下標） |

**傳回：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 類型數學元素

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

建立上標

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的上標（上標） |

**傳回：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 類型數學元素

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

建立上標

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | java.lang.String | 右側的上標（上標） |

**傳回：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 類型數學元素

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

在右側建立下標與上標

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的下標（下標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的上標（上標） |

**傳回：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新的 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 類型數學元素

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

在右側建立下標與上標

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 右側的下標（下標） |
| superscript | java.lang.String | 右側的上標（上標） |

**傳回：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新的 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 類型數學元素

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

在左側建立下標與上標

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 左側的下標（下標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 左側的上標（上標） |

**傳回：**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新的 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 類型數學元素

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

在左側建立下標與上標

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 左側的下標（下標） |
| superscript | java.lang.String | 左側的上標（上標） |

**傳回：**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新的 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 類型數學元素

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

指定從給定參數取得指定次方的數學根號

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 根號的次方參數 |

**傳回：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的 [IMathRadical](../../com.aspose.slides/imathradical) 類型實例

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

指定從給定參數取得指定次方的數學根號

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| degree | java.lang.String | 根號的次方參數 |

**傳回：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的 [IMathRadical](../../com.aspose.slides/imathradical) 類型實例

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

取得上限

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**傳回：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的 [IMathLimit](../../com.aspose.slides/imathlimit) 類型實例

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

取得上限

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | java.lang.String | 上限 |

**傳回：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的 [IMathLimit](../../com.aspose.slides/imathlimit) 類型實例

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

取得下限

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**傳回：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的 [IMathLimit](../../com.aspose.slides/imathlimit) 類型實例

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

取得下限

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**傳回：**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的 [IMathLimit](../../com.aspose.slides/imathlimit) 類型實例

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

建立 N 元運算子

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | N 元運算子類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

建立 N 元運算子

> ```
> 範例：
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | N 元運算子類型 |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

放入垂直陣列

> ```
> 範例：
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**傳回：**
[IMathArray](../../com.aspose.slides/imatharray) - 新的 [IMathArray](../../com.aspose.slides/imatharray) 類型實例

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

取得積分

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分上限 |
| limitLocations | int | 上下限位置 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

取得積分

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分上限 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

取得無上下限的積分

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

取得積分

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分下限 |
| upperLimit | java.lang.String | 積分上限 |
| limitLocations | int | 上下限位置 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

取得積分

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分下限 |
| upperLimit | java.lang.String | 積分上限 |

**傳回：**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新的 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 類型實例

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

設定音調符號（此元素上方的字元）

> ```
> 範例：
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| accentCharacter | char | 音調字元。值應在 (U+0300-U+036F) 或 (U+20D0-U+20EF) 範圍內 |

**傳回：**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新的 [IMathAccent](../../com.aspose.slides/imathaccent) 類型實例

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

在此元素上方設定橫線

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**傳回：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的 [IMathBar](../../com.aspose.slides/imathbar) 類型實例

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

在此元素下方設定橫線

> ```
> 範例：
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**傳回：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的 [IMathBar](../../com.aspose.slides/imathbar) 類型實例

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

使用底部大括號將此元素放入群組

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**傳回：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 類型實例

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

使用分組字元（如底部大括號或其他）將此元素放入群組

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| character | char | 分組字元，例如底部大括號 (U+23DF) 或其他 |
| position | int | 分組字元的位置 |
| verticalJustification | int | 分組字元的垂直對齊方式。指定物件相對於基線的對齊。例如，當字元位於物件上方時，VerticalJustification 為 Top 表示物件頂部在基線上；設定為 Bottom 時，物件底部在基線上 |

**傳回：**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新的 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 類型實例

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

將此元素放入邊框盒

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**傳回：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的邊框盒

### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

將此元素放入邊框盒

> ```
> 範例：
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hideTop | boolean | 隱藏上緣 |
| hideBottom | boolean | 隱藏下緣 |
| hideLeft | boolean | 隱藏左緣 |
| hideRight | boolean | 隱藏右緣 |
| strikethroughHorizontal | boolean | 水平刪除線 |
| strikethroughVertical | boolean | 垂直刪除線 |
| strikethroughBottomLeftToTopRight | boolean | 從左下到右上的刪除線 |
| strikethroughTopLeftToBottomRight | boolean | 從左上到右下的刪除線 |

**傳回：**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 包含此元素的邊框盒

### toBox() {#toBox--}
```
public final IMathBox toBox()
```

將此元素放入非視覺盒（邏輯分組），用於將方程式或其他數學文字的組件分組。盒子物件可（例如）作為運算子模擬器（有或無對齊點），作為換行點，或分組以避免行內斷行。

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**傳回：**
[IMathBox](../../com.aspose.slides/imathbox) - 包含此元素的邏輯盒

### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

取得子元素

**傳回：**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) 陣列