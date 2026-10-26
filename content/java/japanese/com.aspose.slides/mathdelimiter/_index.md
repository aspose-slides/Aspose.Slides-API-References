---
title: MathDelimiter
second_title: Java 用 Aspose.Slides API リファレンス
description: 開き括弧や閉じ括弧、波括弧、角括弧、縦棒などの開始文字と終了文字で構成され、内部に1つ以上の数式要素が指定された文字で区切られた区切りオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathdelimiter/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

区切り文字オブジェクトを指定します。これは、開始文字と終了文字（丸括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素が指定された文字で区切られています。例: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | 指定された要素を単一のベース引数として MathDelimiter を初期化します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 区切り文字で区切られた1つ以上の数式要素 |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character は開始（またはオープン）区切り文字を指定します。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character は開始（またはオープン）区切り文字を指定します。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character は区切りオブジェクト内の引数を区切る文字を指定します。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character は区切りオブジェクト内の引数を区切る文字を指定します。 |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character は終了（またはクローズ）区切り文字を指定します。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character は終了（またはクローズ）区切り文字を指定します。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り記号はオペランドの高さに合わせて垂直方向に伸びます。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り記号はオペランドの高さに合わせて垂直方向に伸びます。 |
| [getDelimiterShape()](#getDelimiterShape--) | 区切りオブジェクト内の区切り記号の形状を指定します。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 区切りオブジェクト内の区切り記号の形状を指定します。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 指定された区切り文字を使用して引数を区切ります |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 数式要素を括弧などの指定文字で囲み、フレームとして使用します |
| [getChildren()](#getChildren--) | 子要素を取得します。 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

指定された要素を単一のベース引数として MathDelimiter を初期化します

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 区切り文字が適用されるベース要素です。null でも構いません。 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

区切り文字で区切られた1つ以上の数式要素

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```


**戻り値:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

Delimiter Beginning Character は開始（またはオープン）区切り文字を指定します。数学的区切り文字は丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**戻り値:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

Delimiter Beginning Character は開始（またはオープン）区切り文字を指定します。数学的区切り文字は丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

Delimiter Separator Character は区切りオブジェクト内の引数を区切る文字を指定します。デフォルトは '|' です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**戻り値:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

Delimiter Separator Character は区切りオブジェクト内の引数を区切る文字を指定します。デフォルトは '|' です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

Delimiter Ending Character は終了（またはクローズ）区切り文字を指定します。数学的区切り文字は丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**戻り値:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

Delimiter Ending Character は終了（またはクローズ）区切り文字を指定します。数学的区切り文字は丸括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')'です。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り記号はオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**戻り値:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り記号はオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

区切りオブジェクト内の区切り記号の形状を指定します。MathDelimiterShape.Centered の場合、区切り記号は数式テキストの数学軸の周りに中心に配置され、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、区切り記号の高さと形状は内容に完全に合わせて変更されます。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**戻り値:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

区切りオブジェクト内の区切り記号の形状を指定します。MathDelimiterShape.Centered の場合、区切り記号は数式テキストの数学軸の周りに中心に配置され、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、区切り記号の高さと形状は内容に完全に合わせて変更されます。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

指定された区切り文字を使用して引数を区切ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | 区切り文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 区切り文字を適用した後のこのオブジェクト
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

数式要素を括弧などの指定文字で囲み、フレームとして使用します

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char | 開始文字（通常は左括弧） |
| endingCharacter | char | 終了文字（通常は右括弧） |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - beginningCharacter と endingCharacter が null の場合、対応するプロパティにのみ値が設定され新しいオブジェクトは作成されません（このインスタンスを返します）。それ以外の場合、指定された文字でフレーム化された Delimiter 型の新しい数式要素を返し、[MathDelimiter](../../com.aspose.slides/mathdelimiter) のインスタンスがその内部にフレームとして含まれます。
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps