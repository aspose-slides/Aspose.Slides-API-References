---
title: IMathElement
second_title: Aspose.Slides for Java API リファレンス
description: 任意の数学要素（分数、数学テキスト、関数、複数要素の式など）のベースインターフェイス
type: docs
url: /ja/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

任意の数学要素（分数、数学テキスト、関数、複数要素の式など）のベースインターフェイス

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChildren()](#getChildren--) | 子要素を取得します |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 数学要素を結合して数学ブロックを形成します |
| [join(String mathText)](#join-java.lang.String-) | 数学テキストを結合して数学ブロックを形成します |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | この分子と指定された分母で分数を作成します |
| [divide(String denominator)](#divide-java.lang.String-) | この分子と指定された分母で分数を作成します |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成します |
| [enclose()](#enclose--) | 数学要素を括弧で囲みます |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | この要素を括弧やその他文字でフレーム化して囲みます |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | このインスタンスを関数名として引数の関数を取ります |
| [function(String functionArgument)](#function-java.lang.String-) | このインスタンスを関数名として引数の関数を取ります |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | このインスタンスを引数として指定された関数を取ります |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | このインスタンスを引数として指定された関数を取ります |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | このインスタンスを引数として指定された関数を取ります |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | このインスタンスを引数として指定された関数と追加の引数を取ります |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | このインスタンスを引数として指定された関数と追加の引数を取ります |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 下付文字を作成します |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 下付文字を作成します |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 上付文字を作成します |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 上付文字を作成します |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 右側に下付文字と上付文字を作成します |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 右側に下付文字と上付文字を作成します |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 左側に下付文字と上付文字を作成します |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 左側に下付文字と上付文字を作成します |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定された引数から指定された次数の数学的根を指定します |
| [radical(String degree)](#radical-java.lang.String-) | 指定された引数から指定された次数の数学的根を指定します |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 上限を取ります |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 上限を取ります |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 下限を取ります |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 下限を取ります |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N元演算子を作成します |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N元演算子を作成します |
| [toMathArray()](#toMathArray--) | 縦配列に配置します |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 積分を取ります |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 積分を取ります |
| [integral(int integralType)](#integral-int-) | 限界なしで積分を取ります |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 積分を取ります |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 積分を取ります |
| [accent(char accentCharacter)](#accent-char-) | アクセント記号（要素の上部にある文字）を設定します |
| [overbar()](#overbar--) | 要素の上部にバーを設定します |
| [underbar()](#underbar--) | 要素の下部にバーを設定します |
| [group()](#group--) | 下カッコで要素をグループ化します |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 下カッコやその他文字で要素をグループ化します |
| [toBorderBox()](#toBorderBox--) | 要素を境界ボックスに配置します |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 要素を境界ボックスに配置します |
| [toBox()](#toBox--) | 要素を非表示ボックス（論理的なグループ化）に配置し、等式や他の数学テキストの構成要素をグループ化します |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```


子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```


数学要素を結合して数学ブロックを形成します

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 結合する要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - このインスタンスと指定された引数を含む新しい IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```


数学テキストを結合して数学ブロックを形成します

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | 結合する数学テキスト |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - このインスタンスと指定された引数を含む新しい IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```


この分子と指定された分母で分数を作成します

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```


この分子と指定された分母で分数を作成します

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```


指定されたタイプの分数を、この分子と指定された分母で作成します

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数タイプ: Bar, NoBar, Skewed, Linear |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```


指定されたタイプの分数を、この分子と指定された分母で作成します

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |
| fractionType | int | 分数タイプ: Bar, NoBar, Skewed, Linear |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```


数学要素を括弧で囲みます

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```


**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 括弧を含むタイプ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) の数学要素
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


この要素を括弧やその他文字でフレーム化して囲みます

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char | 開始文字（通常は左括弧） |
| endingCharacter | char | 終了文字（通常は右括弧） |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 指定された文字でフレーム化されたタイプ [IMathDelimiter](../../com.aspose.slides/imathdelimiter) の数学要素
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```
このインスタンスを関数名として、引数の関数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```


このインスタンスを関数名として、引数の関数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionArgument | java.lang.String | 関数の引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```


このインスタンスを引数として、指定された関数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 関数名 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```


このインスタンスを引数として、指定された関数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionName | java.lang.String | 関数名 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```


このインスタンスを引数として、指定された関数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfOneArgument.ArcSin);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 1 引数の共通関数タイプのいずれか |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```


このインスタンスを引数として、指定された関数と追加引数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' の底が '5' の対数を返します
```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプのいずれか: Log、Lim、Min、Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の種類に応じた追加引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```


このインスタンスを引数として、指定された関数と追加引数を取得します

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' の底が '5' の対数を返します
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプのいずれか: Log、Lim、Min、Max |
| additionalArgument | java.lang.String | 関数の種類に応じた追加引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - 型 [IMathFunction](../../com.aspose.slides/imathfunction) の新しい数式要素  
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSubscriptElement setSubscript(IMathElement subscript)
```


下付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側に下付きインデックスを付けた下付き文字 |

**戻り値:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 型 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) の新しい数式要素  
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public abstract IMathSubscriptElement setSubscript(String subscript)
```


下付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 右側に下付きインデックスを付けた下付き文字 |

**戻り値:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 型 [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) の新しい数式要素  
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public abstract IMathSuperscriptElement setSuperscript(IMathElement superscript)
```


上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側に上付きインデックスを付けた上付き文字 |

**戻り値:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 型 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) の新しい数式要素  
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public abstract IMathSuperscriptElement setSuperscript(String superscript)
```


上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | java.lang.String | 右側に上付きインデックスを付けた上付き文字 |

**戻り値:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 型 [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) の新しい数式要素  
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```


右側に下付き文字と上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側に下付きインデックスを付けた下付き文字 |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側に上付きインデックスを付けた上付き文字 |

**戻り値:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 型 [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) の新しい数式要素  
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```
右側に下付き文字と上付き文字を作成します

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 下付き文字（右側の下付き） |
| superscript | java.lang.String | 上付き文字（右側の上付き） |

**戻り値:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新しい数式要素のタイプ [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```


左側に下付き文字と上付き文字を作成します

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 下付き文字（左側の下付き） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 上付き文字（左側の上付き） |

**戻り値:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新しい数式要素のタイプ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```


左側に下付き文字と上付き文字を作成します

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 下付き文字（左側の下付き） |
| superscript | java.lang.String | 上付き文字（左側の上付き） |

**戻り値:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新しい数式要素のタイプ [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```


指定された引数から指定された次数の数学的根を指定します。

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | ラジカルの引数 |

**戻り値:**
[IMathRadical](../../com.aspose.slides/imathradical) - 型 [IMathRadical](../../com.aspose.slides/imathradical) の新しいインスタンス
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```


指定された引数から指定された次数の数学的根を指定します。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| degree | java.lang.String | ラジカルの引数 |

**戻り値:**
[IMathRadical](../../com.aspose.slides/imathradical) - 型 [IMathRadical](../../com.aspose.slides/imathradical) の新しいインスタンス
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```


上限を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 型 [IMathLimit](../../com.aspose.slides/imathlimit) の新しいインスタンス
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```


上限を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 上限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 型 [IMathLimit](../../com.aspose.slides/imathlimit) の新しいインスタンス
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```


下限を取ります

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 型 [IMathLimit](../../com.aspose.slides/imathlimit) の新しいインスタンス
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```


下限を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 型 [IMathLimit](../../com.aspose.slides/imathlimit) の新しいインスタンス
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```


N 進演算子を作成します

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | N 進演算子のタイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```


N 進演算子を作成します

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | N 進演算子のタイプ |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```


垂直配列に配置します

--------------------

> ```
> 例:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - 型 [IMathArray](../../com.aspose.slides/imatharray) の新しいインスタンス
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```


積分を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分のタイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |
| limitLocations | int | 限界の位置 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```


積分を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分のタイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```


限界なしで積分を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分のタイプ |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```


積分を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分のタイプ |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |
| limitLocations | int | 限界の位置 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```


積分を取ります

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分のタイプ |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 型 [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) の新しいインスタンス
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```


この要素の上にアクセント記号（文字）を設定します

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| accentCharacter | char | アクセント文字。範囲は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) です |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 型 [IMathAccent](../../com.aspose.slides/imathaccent) の新しいインスタンス
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```


この要素の上にバーを設定します

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 型 [IMathBar](../../com.aspose.slides/imathbar) の新しいインスタンス
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```


この要素の下にバーを設定します

--------------------

> ```
> 例:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```


**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 型 [IMathBar](../../com.aspose.slides/imathbar) の新しいインスタンス
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```


下側の波かっこを使用してこの要素をグループに配置します

--------------------

> ```
> 例:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 型 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) の新しいインスタンス
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```


下側の波かっこや他の文字など、グループ化文字を使用してこの要素をグループに配置します

--------------------

> ```
> 例:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) などのグループ化文字 |
| position | int | グループ化文字の位置 |
| verticalJustification | int | グループ文字の垂直方向の位置揃え。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、Top の VerticalJustification はオブジェクトの上端がベースライン上にあることを示し、Bottom に設定するとオブジェクトの下端がベースライン上になります |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 型 [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) の新しいインスタンス
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```


この要素を境界ボックスに配置します

--------------------

> ```
> 例:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置された境界ボックス
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


この要素を境界ボックスに配置します

--------------------

> ```
> 例:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hideTop | boolean | 上側のエッジを非表示 |
| hideBottom | boolean | 下側のエッジを非表示 |
| hideLeft | boolean | 左側のエッジを非表示 |
| hideRight | boolean | 右側のエッジを非表示 |
| strikethroughHorizontal | boolean | 境界ボックスの水平取り消し線 |
| strikethroughVertical | boolean | 境界ボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | 境界ボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | 境界ボックスの左上から右下への取り消し線 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置された境界ボックス
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```


この要素を非表示ボックス（論理的グループ）に配置します。これは数式や他の数式テキストのコンポーネントをグループ化するために使用されます。ボックス化されたオブジェクトは、たとえば、配置ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、行分割を許可しないようにグループ化したりできます。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**戻り値:**
[IMathBox](../../com.aspose.slides/imathbox) - この要素が内部に配置された論理ボックス