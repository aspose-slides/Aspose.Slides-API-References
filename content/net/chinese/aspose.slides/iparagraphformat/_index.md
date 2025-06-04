---
title: IParagraphFormat
second_title: Aspose.Sildes for .NET API Reference
description: 这个类包含段落格式属性。与 IParagraphFormatEffectiveData../iparagraphformateffectivedata 不同，这个类的所有属性都是可写的。
type: docs
weight: 6390
url: /zh/aspose.slides/iparagraphformat/
---

## IParagraphFormat 接口

这个类包含段落格式属性。与 [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) 不同，这个类的所有属性都是可写的。

```csharp
public interface IParagraphFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | 返回或设置段落中的文本对齐，不继承。读/写 [`TextAlignment`](../textalignment)。 |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | 返回段落的项目符号格式。只读 [`IBulletFormat`](../ibulletformat)。 |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | 返回段落的默认部分格式。不适用继承。只读 [`IPortionFormat`](../iportionformat)。 |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | 返回或设置默认制表符大小，不继承。读/写 Single。 |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | 返回或设置段落的深度。值 0 表示未定义的值。读/写 Int16。 |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | 确定段落中是否使用东亚换行。不适用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | 返回或设置段落中的字体对齐，不继承。读/写 [`FontAlignment`](../fontalignment)。 |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | 确定段落中是否使用悬挂标点。不适用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | 返回或设置段落首行缩进/悬挂缩进，不继承。悬挂缩进可以用负值定义。读/写 Single。 |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | 确定段落中是否使用拉丁换行。不适用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | 返回或设置段落的左边距，不继承。读/写 Single。 |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | 返回或设置段落的右边距，不继承。读/写 Single。 |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | 确定段落中是否使用从右到左的书写方向。不适用继承。读/写 [`NullableBool`](../nullablebool)。 |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | 返回或设置段落最后一行后面的空白量，不继承。正值表示白色空间应为字体大小的百分比。负值指定白色空间的大小，单位为点。读/写 Single。 |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | 返回或设置段落第一行前面的空白量，不继承。正值表示白色空间应为字体大小的百分比。负值指定白色空间的大小，单位为点。读/写 Single。 |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | 返回或设置段落基线之间的空白量。正值表示百分比，负值表示点数大小。不适用继承。读/写 Single。 |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | 返回段落的制表符。不适用继承。只读 [`ITabCollection`](../itabcollection)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | 获取应用了继承的有效段落格式数据。 |

### 备注

这个类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下你会得到表示“未定义”的值。

为了获取包含继承的有效格式参数值，你需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) 实例。

### 另请参阅

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)