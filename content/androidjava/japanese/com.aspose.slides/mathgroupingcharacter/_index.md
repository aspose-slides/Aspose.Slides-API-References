---
title: MathGroupingCharacter
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: 式の上または下に配置されるグルーピング記号を指定し、通常は要素間の関係を強調します
type: docs
url: /ja/com.aspose.slides/mathgroupingcharacter/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

式の上または下に配置されるグルーピング記号を指定し、通常は要素間の関係を強調します

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | MathGroupingCharacter クラスの新しいインスタンスを、デフォルトのグルーピング文字 U+23DF (BOTTOM CURLY BRACKET) で初期化します |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | MathGroupingCharacter クラスの新しいインスタンスを初期化します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getCharacter()](#getCharacter--) | グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | グルーピング文字の位置。 |
| [setPosition(int value)](#setPosition-int-) | グルーピング文字の位置。 |
| [getVerticalJustification()](#getVerticalJustification--) | グループ文字の垂直方向の配置。 |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | グループ文字の垂直方向の配置。 |
| [getChildren()](#getChildren--) | 子要素を取得 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

MathGroupingCharacter クラスの新しいインスタンスを、デフォルトのグルーピング文字 U+23DF (BOTTOM CURLY BRACKET) で初期化します

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーが適用されるベース要素 |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

MathGroupingCharacter クラスの新しいインスタンスを初期化します

--------------------

> ```
> 例:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーが適用されるベース要素 |
| character | char | グルーピング文字 |
| position | int | グルーピング文字の位置 |
| verticalJustification | int | グループ文字の垂直方向の配置 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final char getCharacter()
```

グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 下の丸括弧
> ```

**戻り値:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

グルーピング文字 デフォルト値: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // 下の丸括弧
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
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
public final void setPosition(int value)
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
public final int getVerticalJustification()
```

グループ文字の垂直方向の配置。オブジェクトのベースラインに対する位置合わせを指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification の Top はオブジェクトの上部がベースラインに合わせられることを意味します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上になります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

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
public final void setVerticalJustification(int value)
```

グループ文字の垂直方向の配置。オブジェクトのベースラインに対する位置合わせを指定します。たとえば、グループ文字がオブジェクトの上にある場合、VerticalJustification の Top はオブジェクトの上部がベースラインに合わせられることを意味します。VerticalJustification が Bottom に設定されている場合、オブジェクトの下部がベースライン上になります。デフォルト: Position=Top の場合は Bottom、Position=Bottom の場合は Top

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps