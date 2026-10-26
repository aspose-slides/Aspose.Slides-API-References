---
title: IMathElement
second_title: Aspose.Slides for Android via Java API Reference
description: 任意の数学要素（分数、数式テキスト、関数、複数要素を含む式など）の基本インターフェイス
type: docs
url: /ja/com.aspose.slides/imathelement/
---```
public interface IMathElement
```

任意の数学要素（分数、数式テキスト、関数、複数要素を含む式など）の基本インターフェイス

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChildren()](#getChildren--) | 子要素を取得 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 数学要素を結合し、数学ブロックを形成 |
| [join(String mathText)](#join-java.lang.String-) | 数学テキストを結合し、数学ブロックを形成 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | この分子と指定された分母で分数を作成 |
| [divide(String denominator)](#divide-java.lang.String-) | この分子と指定された分母で分数を作成 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成 |
| [enclose()](#enclose--) | 数学要素を丸括弧で囲む |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 指定された文字（括弧など）で要素をフレーム化して囲む |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | このインスタンスを関数名として、引数の関数を取る |
| [function(String functionArgument)](#function-java.lang.String-) | このインスタンスを関数名として、引数の関数を取る |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | このインスタンスを引数として指定された関数を取る |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | このインスタンスを引数として指定された関数を取る |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | このインスタンスを引数として指定された関数を取る |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | このインスタンスを引数として指定された関数と追加引数を取る |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | このインスタンスを引数として指定された関数と追加引数を取る |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 下付き文字を作成 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 下付き文字を作成 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 上付き文字を作成 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 上付き文字を作成 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 右側に下付き文字と上付き文字を作成 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 右側に下付き文字と上付き文字を作成 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 左側に下付き文字と上付き文字を作成 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 左側に下付き文字と上付き文字を作成 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定された引数から指定された次数の数学的根を指定 |
| [radical(String degree)](#radical-java.lang.String-) | 指定された引数から指定された次数の数学的根を指定 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 上限を取る |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 上限を取る |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 下限を取る |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 下限を取る |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N項演算子を作成 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N項演算子を作成 |
| [toMathArray()](#toMathArray--) | 縦配列に配置 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 積分を取る |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 積分を取る |
| [integral(int integralType)](#integral-int-) | 制限なしで積分を取る |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 積分を取る |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 積分を取る |
| [accent(char accentCharacter)](#accent-char-) | アクセント記号を設定（要素の上部の文字） |
| [overbar()](#overbar--) | 要素の上部にバーを設定 |
| [underbar()](#underbar--) | 要素の下部にバーを設定 |
| [group()](#group--) | 下部の波かっこで要素をグループに配置 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 波かっこなどのグループ文字で要素をグループに配置 |
| [toBorderBox()](#toBorderBox--) | 要素をボーダーボックスに配置 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | 要素をボーダーボックスに配置 |
| [toBox()](#toBox--) | 要素を非表示ボックス（論理的グルーピング）に配置し、式や数式テキストのコンポーネントをまとめる |
### getChildren() {#getChildren--}
```
public abstract IMathElement[] getChildren()
```

子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock join(IMathElement mathElement)
```

数学要素を結合し、数学ブロックを形成

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 結合される要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - このインスタンスと指定された引数を含む新しい IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public abstract IMathBlock join(String mathText)
```

数学テキストを結合し、数学ブロックを形成

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | 結合する数学テキスト |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - このインスタンスと指定された引数を含む新しい IMathBlock
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction divide(IMathElement denominator)
```

この分子と指定された分母で分数を作成

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(String denominator) {#divide-java.lang.String-}
```
public abstract IMathFraction divide(String denominator)
```

この分子と指定された分母で分数を作成

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction divide(IMathElement denominator, int fractionType)
```

指定されたタイプの分数を、この分子と指定された分母で作成

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数タイプ: Bar, NoBar, Skewed, Linear |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public abstract IMathFraction divide(String denominator, int fractionType)
```

指定されたタイプの分数を、この分子と指定された分母で作成

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| denominator | java.lang.String | 分母 |
| fractionType | int | 分数タイプ: Bar, NoBar, Skewed, Linear |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい分数
### enclose() {#enclose--}
```
public abstract IMathDelimiter enclose()
```

数学要素を括弧で囲む

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 括弧を含む [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 型の数学要素
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

指定された文字（括弧など）で要素をフレーム化して囲む

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char | 開始文字（通常は左括弧） |
| endingCharacter | char | 終了文字（通常は右括弧） |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 指定された文字でフレーム化された [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 型の数学要素
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction function(IMathElement functionArgument)
```

このインスタンスを関数名として、引数の関数を取る

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
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### function(String functionArgument) {#function-java.lang.String-}
```
public abstract IMathFunction function(String functionArgument)
```

このインスタンスを関数名として、引数の関数を取る

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
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(IMathElement functionName)
```

このインスタンスを引数として指定された関数を取る

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
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(String functionName)
```

このインスタンスを引数として指定された関数を取る

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
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType)
```

このインスタンスを引数として指定された関数を取る

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
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

このインスタンスを引数として指定された関数と追加引数を取る

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' の対数（底は '5'）を返します
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプ（Log, Lim, Min, Max）のいずれか |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数のタイプに応じた追加引数 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public abstract IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

このインスタンスを引数として指定された関数と追加引数を取る

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' の対数（底は '5'）を返します
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプ（Log, Lim, Min, Max）のいずれか |
| additionalArgument | java.lang.String | 関数のタイプに応じた追加引数 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい [IMathFunction](../../com.aspose.slides/imathfunction) 型の数学要素
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の下付き文字（下添え字） |

**戻り値:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新しい [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 型の数学要素
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
| subscript | java.lang.String | 右側の下付き文字（下添え字） |

**戻り値:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - 新しい [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 型の数学要素
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
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の上付き文字（上添え字） |

**戻り値:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新しい [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 型の数学要素
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
| superscript | java.lang.String | 右側の上付き文字（上添え字） |

**戻り値:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - 新しい [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 型の数学要素
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
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の下付き文字（下添え字） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の上付き文字（上添え字） |

**戻り値:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新しい [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 型の数学要素
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public abstract IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

右側に下付き文字と上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 左側の下付き文字（下添え字） |
| superscript | java.lang.String | 左側の上付き文字（上添え字） |

**戻り値:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - 新しい [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 型の数学要素
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

左側に下付き文字と上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 左側の下付き文字（下添え字） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 左側の上付き文字（上添え字） |

**戻り値:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新しい [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 型の数学要素
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public abstract IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

左側に下付き文字と上付き文字を作成

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 左側の下付き文字（下添え字） |
| superscript | java.lang.String | 左側の上付き文字（上添え字） |

**戻り値:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - 新しい [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) 型の数学要素
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical radical(IMathElement degree)
```

指定された引数から指定された次数の数学的根を指定

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | ルートの次数 |

**戻り値:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) 型の新しいインスタンス
### radical(String degree) {#radical-java.lang.String-}
```
public abstract IMathRadical radical(String degree)
```

指定された引数から指定された次数の数学的根を指定

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| degree | java.lang.String | ルートの次数 |

**戻り値:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical) 型の新しいインスタンス
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

上限を取る

--------------------

> ```
public abstract IMathLimit setUpperLimit(IMathElement limit)
```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) 型の新しいインスタンス
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public abstract IMathLimit setUpperLimit(String limit)
```

上限を取る

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 上限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) 型の新しいインスタンス
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit setLowerLimit(IMathElement limit)
```

下限を取る

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) 型の新しいインスタンス
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public abstract IMathLimit setLowerLimit(String limit)
```

下限を取る

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit) 型の新しいインスタンス
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N項演算子を作成

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | N項演算子のタイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N項演算子を作成

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| type | int | N項演算子のタイプ |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### toMathArray() {#toMathArray--}
```
public abstract IMathArray toMathArray()
```

縦配列に配置

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray) 型の新しいインスタンス
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

積分を取る

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の上限 |
| limitLocations | int | 限界の位置 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

積分を取る

--------------------

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### integral(int integralType) {#integral-int-}
```
public abstract IMathNaryOperator integral(int integralType)
```

制限なしで積分を取る

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

積分を取る

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | java.lang.String | 積分の下限 |
| upperLimit | java.lang.String | 積分の上限 |
| limitLocations | int | 限界の位置 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public abstract IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

積分を取る

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | java.lang.String | 積分の下限 |
| upperLimit | java.lang.String | 積分の上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) 型の新しいインスタンス
### accent(char accentCharacter) {#accent-char-}
```
public abstract IMathAccent accent(char accentCharacter)
```

アクセント記号を設定（要素の上部の文字）

--------------------

> ```
> 例:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| accentCharacter | char | アクセント文字。範囲は (U+0300–U+036F) または (U+20D0–U+20EF) |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - [IMathAccent](../../com.aspose.slides/imathaccent) 型の新しいインスタンス
### overbar() {#overbar--}
```
public abstract IMathBar overbar()
```

要素の上部にバーを設定

--------------------

> ```
> Example:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) 型の新しいインスタンス
### underbar() {#underbar--}
```
public abstract IMathBar underbar()
```

要素の下部にバーを設定

--------------------

> ```
public abstract IMathBar underbar()
```

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar) 型の新しいインスタンス
### group() {#group--}
```
public abstract IMathGroupingCharacter group()
```

下部の波かっこで要素をグループに配置

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 型の新しいインスタンス
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public abstract IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

波かっこなどのグループ文字で要素をグループに配置

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字 |
| position | int | グルーピング文字の位置 |
| verticalJustification | int | グループ文字の垂直配置。ベースラインに対する位置を指定。例：文字がオブジェクトの上にある場合、Top は上端がベースラインに合わせられる；Bottom は下端がベースラインに合わせられる |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) 型の新しいインスタンス
### toBorderBox() {#toBorderBox--}
```
public abstract IMathBorderBox toBorderBox()
```

要素をボーダーボックスに配置

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置されたボーダーボックス
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

要素をボーダーボックスに配置

--------------------

> ```
> 例:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hideTop | boolean | 上エッジを非表示 |
| hideBottom | boolean | 下エッジを非表示 |
| hideLeft | boolean | 左エッジを非表示 |
| hideRight | boolean | 右エッジを非表示 |
| strikethroughHorizontal | boolean | ボーダーボックスの水平打ち消し線 |
| strikethroughVertical | boolean | ボーダーボックスの垂直打ち消し線 |
| strikethroughBottomLeftToTopRight | boolean | ボーダーボックスの左下から右上への打ち消し線 |
| strikethroughTopLeftToBottomRight | boolean | ボーダーボックスの左上から右下への打ち消し線 |

**戻り値:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置されたボーダーボックス
### toBox() {#toBox--}
```
public abstract IMathBox toBox()
```

要素を非表示ボックス（論理的グルーピング）に配置。等式やその他の数式テキストのコンポーネントをまとめるために使用され、演算子エミュレータとして（整列ポイントの有無に関わらず）機能したり、改行点として、または改行を許可しないようにグループ化したりすることができる。

--------------------

> ```
> 例:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```

**戻り値:**
[IMathBox](../../com.aspose.slides/imathbox) - この要素が内部に配置された論理ボックス