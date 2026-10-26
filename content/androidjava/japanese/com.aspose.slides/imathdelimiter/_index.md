---
title: IMathDelimiter
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 丸括弧、波括弧、角括弧、縦棒などの開き文字と閉じ文字で構成され、内部に1つ以上の数式要素が指定された文字で区切られる区切り文字オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathdelimiter/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathDelimiter extends IMathElement
```

区切り文字オブジェクトを指定します。開き文字と閉じ文字（丸括弧、波括弧、角括弧、縦棒など）で構成され、内部に1つ以上の数式要素が指定された文字で区切られます。例: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

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
| [getArguments()](#getArguments--) | 区切り文字で区切られた1つ以上の数式要素 |
| [getBeginningCharacter()](#getBeginningCharacter--) | Delimiter Beginning Character は開始（開く）区切り文字を指定します。 |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | Delimiter Beginning Character は開始（開く）区切り文字を指定します。 |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | Delimiter Separator Character は区切り文字オブジェクト内で引数を区切る文字を指定します。 |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | Delimiter Separator Character は区切り文字オブジェクト内で引数を区切る文字を指定します。 |
| [getEndingCharacter()](#getEndingCharacter--) | Delimiter Ending Character は終了（閉じる）区切り文字を指定します。 |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | Delimiter Ending Character は終了（閉じる）区切り文字を指定します。 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り文字は被演算子の高さに合わせて垂直に伸びます。 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り文字は被演算子の高さに合わせて垂直に伸びます。 |
| [getDelimiterShape()](#getDelimiterShape--) | 区切り文字オブジェクト内の区切り文字の形状を指定します。 |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | 区切り文字オブジェクト内の区切り文字の形状を指定します。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 指定された区切り文字を使用して引数を区切ります |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
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
public abstract char getBeginningCharacter()
```

Delimiter Beginning Character は開始（開く）区切り文字を指定します。数式の区切り文字は丸括弧、角括弧、波括弧などです。デフォルト値: '('.

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

Delimiter Beginning Character は開始（開く）区切り文字を指定します。数式の区切り文字は丸括弧、角括弧、波括弧などです。デフォルト値: '('.

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
public abstract char getSeparatorCharacter()
```

Delimiter Separator Character は区切り文字オブジェクト内で引数を区切る文字を指定します。デフォルト: '|'.

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

Delimiter Separator Character は区切り文字オブジェクト内で引数を区切る文字を指定します。デフォルト: '|'.

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
public abstract char getEndingCharacter()
```

Delimiter Ending Character は終了（閉じる）区切り文字を指定します。数式の区切り文字は丸括弧、角括弧、波括弧などです。デフォルト値: ')'.

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

Delimiter Ending Character は終了（閉じる）区切り文字を指定します。数式の区切り文字は丸括弧、角括弧、波括弧などです。デフォルト値: ')'.

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
public abstract boolean getGrowToMatchOperandHeight()
```

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り文字は被演算子の高さに合わせて垂直に伸びます。デフォルト値は true

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

BeginningCharacter、SeparatorCharacter、EndingCharacter の伸長を指定します。true の場合、区切り文字は被演算子の高さに合わせて垂直に伸びます。デフォルト値は true

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
public abstract int getDelimiterShape()
```

区切り文字オブジェクト内の区切り文字の形状を指定します。MathDelimiterShape.Centered の場合、区切り文字は数式テキストの軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、高さと形状が内容に正確に一致するように変更されます。

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

区切り文字オブジェクト内の区切り文字の形状を指定します。MathDelimiterShape.Centered の場合、区切り文字は数式テキストの軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。MathDelimiterShape.Match の場合、高さと形状が内容に正確に一致するように変更されます。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char | 区切り文字 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 区切り文字を適用した後のこのオブジェクト