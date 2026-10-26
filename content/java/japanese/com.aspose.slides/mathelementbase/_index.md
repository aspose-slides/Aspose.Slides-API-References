---
title: MathElementBase
second_title: Aspose.Slides for Java API リファレンス
description: IMathElement の基本クラスで、すべての派生クラスで共通するいくつかのメソッドの実装を提供します。内部使用のみ。
type: docs
url: /ja/com.aspose.slides/mathelementbase/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject  
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

すべての派生クラスで共通のいくつかのメソッドの実装を含む IMathElement の基底クラスです。内部使用のみです。派生クラスは IMathElement でなければなりません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Parent_Immediate オブジェクトを返します。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 数学要素を結合し、数学ブロックを形成します。 |
| [join(String mathText)](#join-java.lang.String-) | 数学テキストを結合し、数学ブロックを形成します。 |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | 指定された分母とこの分子で分数を作成します。 |
| [divide(String denominator)](#divide-java.lang.String-) | 指定された分母とこの分子で分数を作成します。 |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成します。 |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | 指定されたタイプの分数を、この分子と指定された分母で作成します。 |
| [enclose()](#enclose--) | 数学要素を括弧で囲みます。 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 数学要素を括弧やその他の文字など、指定された文字で囲みます。 |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | このインスタンスを関数名として、引数の関数を取得します。 |
| [function(String functionArgument)](#function-java.lang.String-) | このインスタンスを関数名として、引数の関数を取得します。 |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | このインスタンスを引数として、指定された関数を取得します。 |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | このインスタンスを引数として、指定された関数を取得します。 |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | このインスタンスを引数として、指定された関数を取得します。 |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | このインスタンスを引数として、指定された関数を取得し、追加の引数を指定します。 |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | このインスタンスを引数として、指定された関数を取得し、追加の引数を指定します。 |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | 下付き文字を作成します。 |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | 下付き文字を作成します。 |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | 上付き文字を作成します。 |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | 上付き文字を作成します。 |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 右側に下付き文字と上付き文字を作成します。 |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | 右側に下付き文字と上付き文字を作成します。 |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) : | 左側に下付き文字と上付き文字を作成します。 |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | 左側に下付き文字と上付き文字を作成します。 |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | 指定された引数から、指定された次数の数学的ルートを指定します。 |
| [radical(String degree)](#radical-java.lang.String-) | 指定された引数から、指定された次数の数学的ルートを指定します。 |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | 上限を取得します。 |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | 上限を取得します。 |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | 下限を取得します。 |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | 下限を取得します。 |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | N元演算子を作成します。 |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | N元演算子を作成します。 |
| [toMathArray()](#toMathArray--) | 垂直配列を配置します。 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 積分を取得します。 |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 積分を取得します。 |
| [integral(int integralType)](#integral-int-) | 上限・下限なしで積分を取得します。 |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | 積分を取得します。 |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | 積分を取得します。 |
| [accent(char accentCharacter)](#accent-char-) | アクセント記号（この要素の上部にある文字）を設定します。 |
| [overbar()](#overbar--) | この要素の上部にバーを設定します。 |
| [underbar()](#underbar--) | この要素の下部にバーを設定します。 |
| [group()](#group--) | 下部の波括弧を使用してこの要素をグループに配置します。 |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | 下部波括弧やその他のグルーピング文字を使用してこの要素をグループに配置します。 |
| [toBorderBox()](#toBorderBox--) | この要素をボーダーボックスに配置します。 |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | この要素をボーダーボックスに配置します。 |
| [toBox()](#toBox--) | 式や他の数学テキストのコンポーネントをグループ化するために使用される、非表示ボックス（論理的グルーピング）にこの要素を配置します。 |
| [getChildren()](#getChildren--) | 子要素を取得します。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**  
com.aspose.slides.IDOMObject

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

数学要素を結合し、数学ブロックを形成します。

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
public IMathBlock join(String mathText)
```

数学テキストを結合し、数学ブロックを形成します。

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
public final IMathFraction divide(IMathElement denominator)
```

指定された分母とこの分子で分数を作成します。

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
public final IMathFraction divide(String denominator)
```

指定された分母とこの分子で分数を作成します。

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
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

指定されたタイプの分数を、この分子と指定された分母で作成します。

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
public final IMathFraction divide(String denominator, int fractionType)
```

指定されたタイプの分数を、この分子と指定された分母で作成します。

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
public final IMathDelimiter enclose()
```

数学要素を括弧で囲みます。

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
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

数学要素を括弧やその他の文字など、指定された文字で囲みます。

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 指定された文字で枠を作った [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 型の数学要素

### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

このインスタンスを関数名として、引数の関数を取得します。

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

このインスタンスを関数名として、引数の関数を取得します。

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionArgument | java.lang.String | 関数の引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

このインスタンスを引数として、指定された関数を取得します。

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | 関数名 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

このインスタンスを引数として、指定された関数を取得します。

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionName | java.lang.String | 関数名 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

このインスタンスを引数として、指定された関数を取得します。

--------------------

> ```
> Example:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 1 引数の共通関数タイプのいずれか |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

このインスタンスを引数として、指定された関数を取得し、追加の引数を指定します。

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // 'x' の底が '5' の対数を返します
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の種類に応じた追加引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

このインスタンスを引数として、指定された関数を取得し、追加の引数を指定します。

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // 'x' の底が '5' の対数を返します
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functionType | int | 2 引数の共通関数タイプのいずれか: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | 関数の種類に応じた追加引数 |

**戻り値:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - [IMathFunction](../../com.aspose.slides/imathfunction) 型の新しい数学要素

### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

下付き文字を作成します。

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の下付き文字（右側の下インデックス） |

**戻り値:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 型の新しい数学要素

### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

下付き文字を作成します。

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 右側の下付き文字（右側の下インデックス） |

**戻り値:**  
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) 型の新しい数学要素

### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

上付き文字を作成します。

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の上付き文字（右側の上インデックス） |

**戻り値:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 型の新しい数学要素

### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

上付き文字を作成します。

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| superscript | java.lang.String | 右側の上付き文字（右側の上インデックス） |

**戻り値:**  
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) 型の新しい数学要素

### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

右側に下付き文字と上付き文字を作成します。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の下付き文字 |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 右側の上付き文字 |

**戻り値:**  
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) 型の新しい数学要素

### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

右側に下付き文字と上付き文字を作成します。
> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 添え字（右側の下付き） |
| superscript | java.lang.String | 添え字（右側の上付き） |

**Returns:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)型の新しい数式要素

### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

左側に下付きと上付きの添え字を作成します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | 添え字（左側の下付き） |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | 添え字（左側の上付き） |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)型の新しい数式要素

### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

左側に下付きと上付きの添え字を作成します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | java.lang.String | 添え字（左側の下付き） |
| superscript | java.lang.String | 添え字（左側の上付き） |

**Returns:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)型の新しい数式要素

### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

指定された引数から指定された次数の数学的なルートを指定します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | ルートの引数 |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical)型の新しいインスタンス

### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

指定された引数から指定された次数の数学的なルートを指定します

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| degree | java.lang.String | ルートの引数 |

**Returns:**
[IMathRadical](../../com.aspose.slides/imathradical) - [IMathRadical](../../com.aspose.slides/imathradical)型の新しいインスタンス

### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

上限を設定します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit)型の新しいインスタンス

### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

上限を設定します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit)型の新しいインスタンス

### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

下限を設定します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit)型の新しいインスタンス

### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

下限を設定します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | java.lang.String | 下限 |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - [IMathLimit](../../com.aspose.slides/imathlimit)型の新しいインスタンス

### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

N項演算子を作成します

> ```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | N項演算子のタイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

N項演算子を作成します

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | int | N項演算子のタイプ |
| lowerLimit | java.lang.String | 下限 |
| upperLimit | java.lang.String | 上限 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

縦方向の配列に配置します

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - [IMathArray](../../com.aspose.slides/imatharray)型の新しいインスタンス

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

積分を取得します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の上限 |
| limitLocations | int | 限界位置 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

積分を取得します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 積分の上限 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

限界なしで積分を取得します

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

積分を取得します

> ```
> 例:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | java.lang.String | 積分の下限 |
| upperLimit | java.lang.String | 積分の上限 |
| limitLocations | int | 限界位置 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

積分を取得します

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| integralType | int | 積分タイプ |
| lowerLimit | java.lang.String | 積分の下限 |
| upperLimit | java.lang.String | 積分の上限 |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)型の新しいインスタンス

### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

この要素の上にアクセント記号（文字）を設定します

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| accentCharacter | char | アクセント文字。値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - [IMathAccent](../../com.aspose.slides/imathaccent)型の新しいインスタンス

### overbar() {#overbar--}
```
public final IMathBar overbar()
```

この要素の上にバーを設定します

> ```
> 例:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```


**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar)型の新しいインスタンス

### underbar() {#underbar--}
```
public final IMathBar underbar()
```

この要素の下にバーを設定します

> ```
> 例:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Returns:**
[IMathBar](../../com.aspose.slides/imathbar) - [IMathBar](../../com.aspose.slides/imathbar)型の新しいインスタンス

### group() {#group--}
```
public final IMathGroupingCharacter group()
```

下部の波括弧を使用してこの要素をグループ化します

> ```
public final IMathGroupingCharacter group()
```

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)型の新しいインスタンス

### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

下部の波括弧やその他の文字など、グルーピング文字を使用してこの要素をグループ化します

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| character | char | BOTTOM CURLY BRACKET (U+23DF) などのグルーピング文字 |
| position | int | グルーピング文字の位置 |
| verticalJustification | int | グループ文字の垂直位置合わせ。ベースラインに対するオブジェクトの配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification が Top のときオブジェクトの上部がベースライン上にあり、Bottom のとき下部がベースライン上にあります |

**Returns:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)型の新しいインスタンス

### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

この要素をボーダー ボックスに配置します

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置されたボーダー ボックス
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

この要素をボーダー ボックスに配置します

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hideTop | boolean | 上端を非表示 |
| hideBottom | boolean | 下端を非表示 |
| hideLeft | boolean | 左端を非表示 |
| hideRight | boolean | 右端を非表示 |
| strikethroughHorizontal | boolean | ボーダーボックスの水平取り消し線 |
| strikethroughVertical | boolean | ボーダーボックスの垂直取り消し線 |
| strikethroughBottomLeftToTopRight | boolean | ボーダーボックスの左下から右上への取り消し線 |
| strikethroughTopLeftToBottomRight | boolean | ボーダーボックスの左上から右下への取り消し線 |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - この要素が内部に配置されたボーダー ボックス
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

この要素を非表示のボックス（論理的なグルーピング）に配置します。これは数式やその他の数学テキストを構成する要素をグループ化するために使用されます。ボックス化されたオブジェクトは、例えば整列点の有無にかかわらず演算子エミュレータとして、改行点として、または改行が許可されないようにグループ化することができます。

> ```
> 例:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
> ```


**Returns:**
[IMathBox](../../com.aspose.slides/imathbox) - この要素が内部に配置された論理ボックス
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

子要素を取得します

**Returns:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement)の配列