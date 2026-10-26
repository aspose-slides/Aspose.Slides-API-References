---
title: MathElementBase
second_title: Aspose.Slides for Java API 參考
description: IMathElement 的基礎類別，實作了所有衍生類別共有的某些方法，僅供內部使用。
type: docs
url: /zh-hant/com.aspose.slides/mathelementbase/
---
**繼承：**
java.lang.Object

**已實作介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

IMathElement 的基底類別，實作了所有子類別共用的一些方法。僅供內部使用。繼承的類別必須是 IMathElement。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | 返回 Parent_Immediate 物件。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 將數學元素加入並形成數學區塊 |
| [join(String mathText)](#join-java.lang.String-) | 將數學文字加入並形成數學區塊 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 使用此分子與指定的分母建立分數 |
| [divide(String denominator)](#divide-java.lang.String-) | 使用此分子與指定的分母建立分數 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 使用此分子與指定的分母，建立指定類型的分數 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 使用此分子與指定的分母，建立指定類型的分數 |
| [enclose()](#enclose--) | 將數學元素括在括號中 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用指定字符（如括號或其他字符）將數學元素框起 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | 以此實例作為函數名稱，對參數使用函數 |
| [function(String functionArgument)](#function-java.lang.String-) | 以此實例作為函數名稱，對參數使用函數 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | 使用此實例作為參數，調用指定函數 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | 使用此實例作為參數，調用指定函數 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | 使用此實例作為參數，調用指定函數 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | 使用此實例作為參數，調用指定函數並附加指定的額外參數 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | 使用此實例作為參數，調用指定函數並附加指定的額外參數 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 建立下標 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 建立下標 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 建立上標 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 建立上標 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 在右側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 在左側建立下標與上標 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 在左側建立下標與上標 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定給定次方的數學根號，來源於指定參數。 |
| [radical(String degree)](#radical-java.lang.String-) | 指定給定次方的數學根號，來源於指定參數。 |
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
| [accent(char accentCharacter)](#accent-char-) | 設定重音符號（此元素上方的字符） |
| [overbar()](#overbar--) | 在此元素上方設定橫線 |
| [underbar()](#underbar--) | 在此元素下方設定橫線 |
| [group()](#group--) | 使用底部大括號將此元素放入群組 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 使用群組字符（如底部大括號或其他）將此元素放入群組 |
| [toBorderBox()](#toBorderBox--) | 將此元素放入邊框盒中 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 將此元素放入邊框盒中 |
| [toBox()](#toBox--) | 將此元素放入非可視盒（邏輯分組），用於將方程式或其他數學文字的組件分組。 |
| [getChildren()](#getChildren--) | 取得子元素 |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

將數學元素加入並形成數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要加入的元素 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例和指定參數的新的 IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

將數學文字加入並形成數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | java.lang.String | 要加入的數學文字 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例和指定參數的新的 IMathBlock

### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

使用此分子與指定的分母建立分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**返回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

使用此分子與指定的分母建立分數

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |

**返回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

使用此分子與指定的分母，建立指定類型的分數

--------------------

> ```
> 範例：
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型：Bar、NoBar、Skewed、Linear |

**返回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

使用此分子與指定的分母，建立指定類型的分數

--------------------

> ```
> 範例：
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |
| fractionType | int | 分數類型：Bar、NoBar、Skewed、Linear |

**返回：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的分數

### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

將數學元素括在括號中

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含括號的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 類型的數學元素

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定字符（如括號或其他字符）將數學元素框起

--------------------

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常為左括號） |
| endingCharacter | char | 結束字符（通常為右括號） |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含指定字符作為框架的 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 類型的數學元素

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

以此實例作為函數名稱，對參數使用函數

--------------------

> ```
> 範例:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 函數的參數 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

以此實例作為函數名稱，對參數使用函數

--------------------

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionArgument | java.lang.String | 函數的參數 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

使用此實例作為參數，調用指定函數

--------------------

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 函數名稱 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

使用此實例作為參數，調用指定函數

--------------------

> ```
> 範例：
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionName | java.lang.String | 函數名稱 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

使用此實例作為參數，調用指定函數

--------------------

> ```
> 範例：
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 單參數常用函數類型之一 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

使用此實例作為參數，調用指定函數並附加指定的額外參數

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 返回 'x' 以 5 為底的對數
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 雙參數常用函數類型之一：Log、Lim、Min、Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 根據函數類型的額外參數 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

使用此實例作為參數，調用指定函數並附加指定的額外參數

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 返回 'x' 以 5 為底的對數
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| functionType | int | 雙參數常用函數類型之一：Log、Lim、Min、Max |
| additionalArgument | java.lang.String | 根據函數類型的額外參數 |

**返回：**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新的 [IMathFunction](../../com.aspose.slides/imathfunction) 類型的數學元素

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

建立下標

--------------------

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的下標（右下指標） |

**返回：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 類型的數學元素

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

建立下標

--------------------

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 右側的下標（右下指標） |

**返回：**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新的 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 類型的數學元素

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

建立上標

--------------------

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的上標（右上指標） |

**返回：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 類型的數學元素

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

建立上標

--------------------

> ```
> 範例：
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| superscript | java.lang.String | 右側的上標（右上指標） |

**返回：**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新的 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 類型的數學元素

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

在右側建立下標與上標

--------------------

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```


參數：
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的下標（右下指標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側的上標（右上指標） |

**返回：**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新的 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 類型的數學元素

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 下標（右側的下標） |
| superscript | java.lang.String | 上標（右側的上標） |

**返回值:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新數學元素，類型為 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

在左側建立下標和上標

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下標（左側的下標） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上標（左側的上標） |

**返回值:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新數學元素，類型為 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

在左側建立下標和上標

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subscript | java.lang.String | 下標（左側的下標） |
| superscript | java.lang.String | 上標（左側的上標） |

**返回值:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新數學元素，類型為 [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

指定給定次方的數學根，根據指定的參數。

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | 根號的參數 |

**返回值:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新實例，類型為 [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

指定給定次方的數學根，根據指定的參數。

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| degree | java.lang.String | 根號的參數 |

**返回值:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新實例，類型為 [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

取得上限

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制 |

**返回值:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例，類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

取得上限

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | java.lang.String | 限制 |

**返回值:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例，類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

取得下限

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制 |

**返回值:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例，類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

取得下限

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| limit | java.lang.String | 限制 |

**返回值:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新實例，類型為 [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

建立 N 元運算子

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | N 元運算子的類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

建立 N 元運算子

---

> ```
> 範例：
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | N 元運算子的類型 |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

以垂直陣列放入

---

> ```
> 範例：
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**返回值:**
[IMathArray](../../com.aspose.slides/imatharray) - 新實例，類型為 [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

取得積分

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分上限 |
| limitLocations | int | 限制位置 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

取得積分

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分上限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

取得無上下限的積分

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

取得積分

---

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分下限 |
| upperLimit | java.lang.String | 積分上限 |
| limitLocations | int | 限制位置 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

取得積分

---

> ```
> 範例：
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| integralType | int | 積分類型 |
| lowerLimit | java.lang.String | 積分下限 |
| upperLimit | java.lang.String | 積分上限 |

**返回值:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新實例，類型為 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

設定重音標記（此元素上方的字符）

---

> ```
> 範例：
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| accentCharacter | char | 重音字符。值應該在 (U+0300\\u2013U+036F) 或 (U+20D0\\u2013U+20EF) 範圍內 |

**返回值:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新實例，類型為 [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

在此元素頂部設定一條橫線

---

> ```
> 範例：
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**返回值:**
[IMathBar](../../com.aspose.slides/imathbar) - 新實例，類型為 [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

在此元素底部設定一條橫線

---

> ```
> 範例：
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**返回值:**
[IMathBar](../../com.aspose.slides/imathbar) - 新實例，類型為 [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

使用底部大括號將此元素放入群組

---

> ```
> 範例：
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**返回值:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新實例，類型為 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

使用群組字符（例如底部大括號或其他）將此元素放入群組

---

> ```
> 範例：
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| character | char | 分組字符，例如底部大括號 (U+23DF) 或任何其他 |
| position | int | 分組字符的位置 |
| verticalJustification | int | 分組字符的垂直對齊方式。指定對象相對於基線的對齊方式。例如，當分組字符位於對象之上時，Top 的垂直對齊表示對象的頂部落在基線上；當設置為 Bottom 時，對象的底部在基線上 |

**返回值:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新實例，類型為 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

將此元素放入邊框盒

---

> ```
> 範例：
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**返回值:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 邊框盒內含此元素
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

將此元素放入邊框盒

---

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hideTop | boolean | 隱藏頂部邊緣 |
| hideBottom | boolean | 隱藏底部邊緣 |
| hideLeft | boolean | 隱藏左側邊緣 |
| hideRight | boolean | 隱藏右側邊緣 |
| strikethroughHorizontal | boolean | 邊框盒水平刪除線 |
| strikethroughVertical | boolean | 邊框盒垂直刪除線 |
| strikethroughBottomLeftToTopRight | boolean | 邊框盒從左下到右上的刪除線 |
| strikethroughTopLeftToBottomRight | boolean | 邊框盒從左上到右下的刪除線 |

**返回值:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - 邊框盒內含此元素
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

將此元素放入非可視方框（邏輯分組），用於將方程式或其他數學文字的組件分組。盒狀對象可以（例如）作為具有或不具有對齊點的運算子模擬器，作為換行點，或分組以防止在其中換行。

---

> ```
> 範例：
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**返回值:**
[IMathBox](../../com.aspose.slides/imathbox) - 邏輯方框內含此元素
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

取得子元素

**返回值:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) 的陣列