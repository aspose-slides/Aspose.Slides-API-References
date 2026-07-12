---
title: IMathGroupingCharacter
second_title: Aspose.Slides for Android の Java API リファレンス
description: 式の上または下に配置されるグルーピングシンボルを指定します。通常、要素間の関係を強調するために使用されます。
type: docs
url: /ja/com.aspose.slides/imathgroupingcharacter/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

式の上または下に配置されるグルーピングシンボルを指定します。通常、要素間の関係を強調するために使用されます

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getCharacter()](#getCharacter--) | グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | グルーピング文字の位置。 |
| [setPosition(int value)](#setPosition-int-) | グルーピング文字の位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | グループ文字の垂直方向の揃え。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | グループ文字の垂直方向の揃え。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基本引数

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 下括弧
```

**戻り値:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 下括弧
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

グルーピング文字の位置。デフォルト: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

グルーピング文字の位置。デフォルト: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

グループ文字の垂直方向の揃え。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**戻り値:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

グループ文字の垂直方向の揃え。オブジェクトのベースラインに対する配置を指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification の Top はオブジェクトの上部がベースライン上にあることを示します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上にあります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |