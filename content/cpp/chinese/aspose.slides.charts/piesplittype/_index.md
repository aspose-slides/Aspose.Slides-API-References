---
title: PieSplitType
second_title: Aspose.Slides for C++ API 参考
description: 表示在饼形图的嵌套饼图或嵌套条形图中第二个饼或条的拆分点类型。
type: docs
weight: 1665
url: /zh/aspose.slides.charts/piesplittype/
---
## PieSplitType 枚举

表示在饼形图的嵌套饼图或嵌套条形图中第二个饼或条的拆分点类型。

```cpp
enum class PieSplitType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | 指定数据点应使用此图表类型的默认机制进行拆分。 |
| Custom | 1 | 指定数据点应根据 Custom Split 值在饼图和第二个图表之间进行拆分。 |
| ByPercentage | 2 | 指定数据点应通过将百分比低于 Split Position 百分比的点放入第二个图表，从而在饼图和第二个图表之间进行拆分。 |
| ByPos | 3 | 指定数据点应通过将数据点的最后一个 Split Position 放入第二个图表，从而在饼图和第二个图表之间进行拆分。 |
| ByValue | 4 | 指定数据点应通过将值低于 Split Position 的数据点放入第二个图表，从而在饼图和第二个图表之间进行拆分。 |

## 另请参见

* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)