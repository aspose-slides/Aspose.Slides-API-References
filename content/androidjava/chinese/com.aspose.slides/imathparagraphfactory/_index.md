---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /zh/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

允许创建数学段落

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 创建空的数学段落 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 创建数学段落并将指定的数学块放入其中 |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


创建空的数学段落

**返回：**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的数学段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


创建数学段落并将指定的数学块放入其中

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要放入段落的数学块 |

**返回：**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的数学段落