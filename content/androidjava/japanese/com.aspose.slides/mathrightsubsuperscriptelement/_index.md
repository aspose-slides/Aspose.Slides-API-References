---
title: MathRightSubSuperscriptElement
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 基底と、その右側に配置された下付き文字および上付き文字で構成されるサブスクリプト/スーパースクリプトオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathrightsubsuperscriptelement/
---
**継承:** java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)  
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

基底と、基底の右側に配置された下付き文字と上付き文字で構成されるサブスクリプト/スーパースクリプトオブジェクトを指定します。

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRightSubSuperscriptElement クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSubscript()](#getSubscript--) | 下付き文字引数 |
| [getSuperscript()](#getSuperscript--) | 上付き文字引数 |
| [getAlignScripts()](#getAlignScripts--) | 下付き文字/上付き文字の配置を指定します。 |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | 下付き文字/上付き文字の配置を指定します。 |
| [getChildren()](#getChildren--) | 子要素を取得します |

### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

MathRightSubSuperscriptElement クラスの新しいインスタンスを初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

下付き文字引数

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

上付き文字引数

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```

下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は互いに水平に配置されます。false の場合、基底の形状に合わせてカーニングされます。デフォルト値は false です。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**戻り値:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```

下付き文字/上付き文字の配置を指定します。true の場合、下付き文字と上付き文字は互いに水平に配置されます。false の場合、基底の形状に合わせてカーニングされます。デフォルト値は false です。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]