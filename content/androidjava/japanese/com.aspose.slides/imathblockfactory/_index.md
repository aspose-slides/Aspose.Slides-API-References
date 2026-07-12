---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /ja/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

数式ブロックを作成できます

--------------------

For COM comparibility
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 数式ブロックを作成します |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 数式ブロックを作成し、要素を配置します |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 数式ブロックを作成し、要素を配置します |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


数式ブロックを作成します

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数式ブロック
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
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
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


数式ブロックを作成し、要素を配置します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数式要素 |

**戻り値:**
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数式ブロック