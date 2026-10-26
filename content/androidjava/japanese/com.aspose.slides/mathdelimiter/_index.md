---
title: MathDelimiter
second_title: Aspose.Slides for Android の Java API リファレンス
description: 開き文字と閉じ文字（例えば括弧、波括弧、角括弧、縦棒など）で構成され、内部に指定文字で区切られた 1 つ以上の数式要素を含むデリミタオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathdelimiter/
---
**継承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

デリミタオブジェクトを指定します。これは開き文字と閉じ文字（括弧、波括弧、角括弧、縦棒など）で構成され、内部に 1 つ以上の数式要素が指定文字で区切られます。例: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | 指定された要素を単一の基本引数として MathDelimiter を初期化します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 区切り文字で区切られた 1 つ以上の数式要素 |
| [getBeginningCharacter()](#getBeginningCharacter--) | デリミタ開始文字は、開始、または開くデリミタ文字を指定します |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | デリミタ開始文字は、開始、または開くデリミタ文字を指定します |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | デリミタ区切り文字は、デリミタオブジェクト内の引数を区切る文字を指定します |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | デリミタ区切り文字は、デリミタオブジェクト内の引数を区切る文字を指定します |
| [getEndingCharacter()](#getEndingCharacter--) | デリミタ終了文字は、終了、または閉じるデリミタ文字を指定します |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | デリミタ終了文字は、終了、または閉じるデリミタ文字を指定します |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に伸長します |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に伸長します |
| [getDelimiterShape()](#getDelimiterShape--) | デリミタオブジェクト内のデリミタの形状を指定します |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | デリミタオブジェクト内のデリミタの形状を指定します |
| [delimit(char separatorCharacter)](#delimit-char-) | 指定されたデリミタ文字を使用して引数を区切ります |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 数式要素を括弧などの指定文字で囲み、フレームとして使用します |
| [getChildren()](#getChildren--) | 子要素を取得します |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |

### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

指定された要素を単一の基本引数として MathDelimiter を初期化します

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | デリミタが適用されるベース要素です。null にすることも可能です。 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

区切り文字で区切られた 1 つ以上の数式要素

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

デリミタ開始文字は、開始、または開くデリミタ文字を指定します。数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。

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

デリミタ開始文字は、開始、または開くデリミタ文字を指定します。数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。デフォルトは '(' です。

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

デリミタ区切り文字は、デリミタオブジェクト内の引数を区切る文字を指定します。デフォルトは '|' です。

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

デリミタ区切り文字は、デリミタオブジェクト内の引数を区切る文字を指定します。デフォルトは '|' です。

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

デリミタ終了文字は、終了、または閉じるデリミタ文字を指定します。数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')' です。

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

デリミタ終了文字は、終了、または閉じるデリミタ文字を指定します。数学的デリミタは括弧、角括弧、波括弧などの囲み文字です。デフォルトは ')' です。

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

BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に伸長します。デフォルト値は true です

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

BeginningCharacter、SeparatorCharacter、EndingCharacter の成長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直に伸長します。デフォルト値は true です

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

デリミタオブジェクト内のデリミタの形状を指定します。MathDelimiterShape.Centered の場合、デリミタは数式テキストの数学軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、デリミタの高さと形状は内容に正確に一致するように変更されます。

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

デリミタオブジェクト内のデリミタの形状を指定します。MathDelimiterShape.Centered の場合、デリミタは数式テキストの数学軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、デリミタの高さと形状は内容に正確に一致するように変更されます。

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

指定されたデリミタ文字を使用して引数を区切ります

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | デリミタ文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - デリミタ文字を適用した後のこのオブジェクト

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - beginningCharacter と endingCharacter がどちらも null の場合、対応するプロパティにのみ値が設定され、新しいオブジェクトは作成されません（このインスタンスを返します）。それ以外の場合、指定文字でフレーム化された Delimiter 型の新しい数式要素が作成され、[MathDelimiter](../../com.aspose.slides/mathdelimiter) がフレーム内に配置されます

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