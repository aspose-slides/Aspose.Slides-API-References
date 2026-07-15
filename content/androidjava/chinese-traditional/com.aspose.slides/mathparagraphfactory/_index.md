---
title: MathParagraphFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立數學段落
type: docs
url: /zh-hant/com.aspose.slides/mathparagraphfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

允許建立數學段落

--------------------

用於 COM 相容性
## 建構子

| Constructor | Description |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## 方法

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 建立空的數學段落 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 建立數學段落並將指定的數學區塊放入其中 |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```

### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```

建立空的數學段落

**返回：**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的數學段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

建立數學段落並將指定的數學區塊放入其中

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要放入段落的數學區塊 |

**返回：**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的數學段落