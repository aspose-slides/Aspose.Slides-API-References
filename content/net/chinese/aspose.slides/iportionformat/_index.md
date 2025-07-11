---
title: IPortionFormat
second_title: Aspose.Sildes for .NET API Reference
description: 该类包含文本部分格式化属性。与 IPortionFormatEffectiveData../iportionformateffectivedata 不同，所有属性都是可写的。
type: docs
weight: 6530
url: /zh/aspose.slides/iportionformat/
---

## IPortionFormat 接口

该类包含文本部分格式化属性。与 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 不同，所有属性都是可写的。

```csharp
public interface IPortionFormat : IBasePortionFormat, IHyperlinkContainer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIBasePortionFormat](../../aspose.slides/iportionformat/asibaseportionformat) { get; } | 返回 IBasePortionFormat 接口。只读 [`IBasePortionFormat`](../ibaseportionformat)。 |
| [AsIHyperlinkContainer](../../aspose.slides/iportionformat/asihyperlinkcontainer) { get; } | 允许获取基本 IHyperlinkContainer 接口。只读 [`IHyperlinkContainer`](../ihyperlinkcontainer)。 |
| [BookmarkId](../../aspose.slides/iportionformat/bookmarkid) { get; set; } | 返回或设置书签标识符。读写字符串。 |
| [SmartTagClean](../../aspose.slides/iportionformat/smarttagclean) { get; set; } | 确定是否应该清理智能标签。没有应用继承。读写布尔值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetEffective](../../aspose.slides/iportionformat/geteffective)() | 获取应用继承的有效部分格式化数据。 |

### 备注

该类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着在获取值时不应用继承，因此在大多数情况下，您将得到表示“未定义”的值。

为了获取包括继承的有效格式参数值，您需要使用 [`GetEffective`](./geteffective) 方法，该方法返回一个 [`IPortionFormatEffectiveData`](../iportionformateffectivedata) 实例。

### 另请参见

* 接口 [IBasePortionFormat](../ibaseportionformat)
* 接口 [IHyperlinkContainer](../ihyperlinkcontainer)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->