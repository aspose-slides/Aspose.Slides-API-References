---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /ja/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

数式段落を作成できる

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 空の数式段落を作成する |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 数式段落を作成し、指定された数式ブロックを配置する |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

空の数式段落を作成する

**戻り値:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新しい数式段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

数式段落を作成し、指定された数式ブロックを配置する

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 段落に配置する数式ブロック |

**戻り値:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新しい数式段落