---
title: IOverridableText
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表的可覆盖文本。
type: docs
url: /zh/com.aspose.slides/ioverridabletext/
---
**所有实现的接口：**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

表示图表的可覆盖文本。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文本。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用参数 “text” 中的文本初始化 TextFrameForOverriding。 |

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

可以包含富格式文本。如果此属性不为 null，则此格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、值轴的显示单元标签、轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 IFormattedTextContainer.TextFormat 属性进行格式化。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

使用参数 “text” 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则直接更改其文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 用于新 TextFrameForOverriding 的文本。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe) - 文本框 [ITextFrame](../../com.aspose.slides/itextframe)