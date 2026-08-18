---
title: MathDelimiterFactory
second_title: Aspose.Slides for Java API リファレンス
description: 数式デリミタを作成できます
type: docs
url: /ja/com.aspose.slides/mathdelimiterfactory/
---
**継承:**
java.lang.Object

**すべての実装インターフェイス:**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

数式デリミタを作成できます

--------------------

COM 互換性のため
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 要素に適用して数式デリミタを作成します |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 要素に適用して数式デリミタを作成します |
### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```


### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```


要素に適用して数式デリミタを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | デリミタを適用する数式要素 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新しい数式デリミタ
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


数式要素に適用して数式デリミタを作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | デリミタを適用する数式要素 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新しい数式デリミタ