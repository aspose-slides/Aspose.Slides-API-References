---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允許建立數學段落
type: docs
url: /zh-hant/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

允許建立數學段落

--------------------

供 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 建立空的數學段落 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 建立數學段落並在其中放置指定的數學區塊 |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

建立空的數學段落

**傳回:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的數學段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

建立數學段落並在其中放置指定的數學區塊

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要放入段落的數學區塊 |

**傳回:**  
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的數學段落