---
title: MathParagraphFactory
second_title: Aspose.Slides for Java API リファレンス
description: 数式段落を作成できます
type: docs
url: /ja/com.aspose.slides/mathparagraphfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

数式段落を作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 空の数式段落を作成 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 数式段落を作成し、指定された数式ブロックを配置します |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


空の数式段落を作成

**戻り値:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新しい数式段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


数式段落を作成し、指定された数式ブロックを配置します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 段落に配置する数式ブロック |

**戻り値:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新しい数式段落