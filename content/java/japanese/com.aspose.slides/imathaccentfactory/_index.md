---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: 数式アクセントを作成できる
type: docs
url: /ja/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

数式アクセントを作成できる

--------------------

COM互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

指定された数式要素にデフォルトのアクセント文字を適用して数式アクセントを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新しい数式アクセント
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

指定された数式要素にアクセント文字を適用して数式アクセントを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | アクセントを適用する数式要素 |
| accentCharacter | char | アクセント文字 |

**戻り値:**
[IMathAccent](../../com.aspose.slides/imathaccent) - 新しい数式アクセント