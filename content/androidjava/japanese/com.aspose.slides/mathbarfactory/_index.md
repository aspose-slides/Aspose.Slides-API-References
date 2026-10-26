---
title: MathBarFactory
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 数式バーを作成できます
type: docs
url: /ja/com.aspose.slides/mathbarfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

数式バーを作成できます

--------------------

COM 互換性のため
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 要素に適用して数式バーを作成します |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 要素に適用して数式バーを作成します |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```


### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```


要素に適用して数式バーを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーを適用する数式要素 |

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 新しい数式バー要素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```


要素に適用して数式バーを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | バーを適用する数式要素 |
| position | int | バーの位置 |

**戻り値:**
[IMathBar](../../com.aspose.slides/imathbar) - 新しい数式バー要素