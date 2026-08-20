---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學段落
type: docs
url: /zh-hant/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

允許建立數學段落

--------------------

用於 COM 相容性
## Methods

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 建立空的數學段落 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 建立數學段落並將指定的數學區塊放入其中 |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


建立空的數學段落

**Returns:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


建立數學段落並將指定的數學區塊放入其中

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要放入段落的數學區塊 |

**Returns:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - new math paragraph