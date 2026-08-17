---
title: IMathDelimiter
second_title: Aspose.Slides for Java API リファレンス
description: 開き括弧や閉じ括弧、波括弧、角括弧、縦棒などの開閉文字で構成され、内部に1つ以上の数式要素があり、指定された文字で区切られるデリミタオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathdelimiter/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

区切り文字オブジェクトを指定します。開き文字と閉じ文字（丸括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素があり、指定された文字で区切られます。例: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArguments()](#getArguments--) | 1つ以上の数式要素が区切り文字で区切られています |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character は開始（または開く）区切り文字を指定します。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character は開始（または開く）区切り文字を指定します。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character は区切りオブジェクト内の引数を分ける文字を指定します。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character は区切りオブジェクト内の引数を分ける文字を指定します。 |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character は終了（または閉じ）区切り文字を指定します。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character は終了（または閉じ）区切り文字を指定します。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に伸びます。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に伸びます。 |
| [getDelimiterShape()](#getDelimiterShape--) | 区切りオブジェクト内のデリミタの形状を指定します。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 区切りオブジェクト内のデリミタの形状を指定します。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 指定された区切り文字を使用して引数を区切ります |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

1つ以上の数式要素が区切り文字で区切られています

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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character は開始（または開く）区切り文字を指定します。数学的デリミタは丸括弧、角括弧、波括弧などの囲み文字です。デフォルト値: '('。

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
public abstract void setBeginningCharacter(char value)
```

Delimiter Beginning Character は開始（または開く）区切り文字を指定します。数学的デリミタは丸括弧、角括弧、波括弧などの囲み文字です。デフォルト値: '('。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character は区切りオブジェクト内の引数を分ける文字を指定します。デフォルト: '|'。

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
public abstract void setSeparatorCharacter(char value)
```

Delimiter Separator Character は区切りオブジェクト内の引数を分ける文字を指定します。デフォルト: '|'。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getEndingCharacter() {#getEndingCharacter--}
```
public abstract char getEndingCharacter()
```

Delimiter Ending Character は終了（または閉じ）区切り文字を指定します。数学的デリミタは丸括弧、角括弧、波括弧などの囲み文字です。デフォルト値: ')'。

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
public abstract void setEndingCharacter(char value)
```

Delimiter Ending Character は終了（または閉じ）区切り文字を指定します。数学的デリミタは丸括弧、角括弧、波括弧などの囲み文字です。デフォルト値: ')'。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です

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
public abstract void setGrowToMatchOperandHeight(boolean value)
```

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、デリミタはオペランドの高さに合わせて垂直方向に伸びます。デフォルト値は true です

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDelimiterShape() {#getDelimiterShape--}
```
public abstract int getDelimiterShape()
```

区切りオブジェクト内のデリミタの形状を指定します。MathDelimiterShape.Centered の場合、デリミタは数式テキストの数式軸を中心に配置され、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、高さと形状が内容に正確に合わせて変更されます。

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
public abstract void setDelimiterShape(int value)
```

区切りオブジェクト内のデリミタの形状を指定します。MathDelimiterShape.Centered の場合、デリミタは数式テキストの数式軸を中心に配置され、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、高さと形状が内容に正確に合わせて変更されます。

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

指定された区切り文字を使用して引数を区切ります

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.delimit('|');
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | 区切り文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - このオブジェクトは区切り文字を適用した後のものです