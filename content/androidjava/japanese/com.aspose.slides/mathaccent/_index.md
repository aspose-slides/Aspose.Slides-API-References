---
title: MathAccent
second_title: Java API リファレンス（Android 用 Aspose.Slides）
description: ベースと結合用ダイアクリティカルマークから構成されるアクセント機能を指定します。例: ud835udc4eu0301
type: docs
url: /ja/com.aspose.slides/mathaccent/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

アクセント機能を指定します。ベースと結合用のダイアクリティカルマークで構成されます。例: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | 既定のアクセント文字値を使用して、指定された数式要素に適用される数式アクセントを作成します |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | 指定された数式要素に適用される数式アクセントを作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | アクセントが適用された引数 |
| [getCharacter()](#getCharacter--) | Accent Character 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302) |
| [getChildren()](#getChildren--) | 子要素を取得します |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |

### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

指定された数式要素に既定のアクセント文字値を使用して適用される数式アクセントを作成します

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

指定された数式要素に適用される数式アクセントを作成します

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |
| accentCharacter | char | アクセント文字 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

アクセントが適用された引数

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**戻り値:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character 値は (U+0300\\u2013U+036F) または (U+20D0\\u2013U+20EF) の範囲内である必要があります デフォルト値: 結合サーカムフレックスアクセント (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

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

Control Character Properties

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps