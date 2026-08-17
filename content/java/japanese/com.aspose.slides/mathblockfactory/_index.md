---
title: MathBlockFactory
second_title: Aspose.Slides for Java API リファレンス
description: 数式ブロックを作成できます
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

数式ブロックを作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 数式ブロックを作成 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 数式ブロックを作成し、その要素を配置 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 数式ブロックを作成し、要素を配置 |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```

### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

数式ブロックを作成

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数式ブロック
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

数式ブロックを作成し、要素を配置します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 数式要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数式ブロック
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

数式ブロックを作成し、要素を配置します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数式要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数式ブロック