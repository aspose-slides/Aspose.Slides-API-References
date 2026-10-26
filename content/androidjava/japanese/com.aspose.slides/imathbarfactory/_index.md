---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math bar
type: docs
url: /ja/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

数式バーを作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 要素に適用して数式バーを作成します |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 要素に適用して数式バーを作成します |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

要素に適用して数式バーを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーを適用する数式要素 |

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 新しい数式バー要素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

要素に適用して数式バーを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーを適用する数式要素 |
| position | int | バーの位置 |

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 新しい数式バー要素