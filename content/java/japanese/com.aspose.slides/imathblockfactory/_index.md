---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: 数学ブロックを作成できます
type: docs
url: /ja/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

数学ブロックを作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 数学ブロックを作成します |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 数学ブロックを作成し、要素をその中に配置します |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 数学ブロックを作成し、要素をその中に配置します |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

数学ブロックを作成します

**戻り値:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

数学ブロックを作成し、要素をその中に配置します

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 数学要素 |

**戻り値:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

数学ブロックを作成し、要素をその中に配置します

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数学要素 |

**戻り値:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新しい数学ブロック