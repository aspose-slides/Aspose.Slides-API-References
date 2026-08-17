---
title: ChartPortionFormat
second_title: Aspose.Slides 的 Java API 参考
description: 此类包含在图表中使用的图表部分格式化属性。
type: docs
url: /zh/com.aspose.slides/chartportionformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**所有实现的接口:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

此类包含在图表中使用的图表部分格式化属性。与 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此类的所有属性都是可写的。

--------------------

此类用于返回和操作为特定部分定义的文本部分格式化属性。这意味着在获取值时不适用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式化参数值，您需要使用 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 方法，该方法返回一个 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 实例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回:**
long