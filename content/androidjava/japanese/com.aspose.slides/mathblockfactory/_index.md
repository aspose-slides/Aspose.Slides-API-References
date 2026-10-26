---
title: MathBlockFactory
second_title: Java API リファレンス経由の Android 用 Aspose.Slides
description: 数学ブロックを作成できるようにします
type: docs
url: /ja/com.aspose.slides/mathblockfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

数学ブロックを作成することを許可します

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 数学ブロックを作成する |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 数学ブロックを作成し、その要素を配置する |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 数学ブロックを作成し、要素を配置する |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


数学ブロックを作成する

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


数学ブロックを作成し、その要素を配置する

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 数学要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


数学ブロックを作成し、要素を配置する

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数学要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック