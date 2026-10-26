---
title: MathAccentFactory
second_title: Aspose.Slides for Android の Java API リファレンス
description: 数式アクセントを作成できます
type: docs
url: /ja/com.aspose.slides/mathaccentfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

数式アクセントを作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | 指定された数式要素にデフォルトのアクセント文字値を適用した数式アクセントを作成します |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | 指定された数式要素にアクセントを適用した数式アクセントを作成します |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

指定された数式要素にデフォルトのアクセント文字値を適用した数式アクセントを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新しい数式アクセント
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

指定された数式要素にアクセントを適用した数式アクセントを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |
| accentCharacter | char | アクセント文字 |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新しい数式アクセント