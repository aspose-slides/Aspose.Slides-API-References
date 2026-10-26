---
title: MathParagraphFactory
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 允许创建数学段落
type: docs
url: /zh/com.aspose.slides/mathparagraphfactory/
---
**继承:**
java.lang.Object

**所有已实现的接口:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

允许创建数学段落

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | 创建空数学段落 |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | 创建数学段落并将指定的数学块放入其中 |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```

### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```

创建空数学段落

**返回:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的数学段落
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

创建数学段落并将指定的数学块放入其中

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要放入段落的数学块 |

**返回:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - 新的数学段落