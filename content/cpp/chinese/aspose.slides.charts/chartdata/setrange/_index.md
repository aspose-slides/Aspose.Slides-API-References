---
title: SetRange()
second_title: Aspose.Slides for C++ API 参考
description: 设置图表数据范围。Series 和 类别 将根据新的数据范围进行更新。如果数据范围中的 Series 数量大于图表数据中的 Series 计数，则会在当前集合的末尾添加与当前集合中最后一个 Series 具有相同类型的额外 Series。
type: docs
weight: 170
url: /zh/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) 方法


设置图表数据范围。Series 和 类别 将根据新的数据范围进行更新。如果数据范围中的系列数量大于图表数据中的系列计数，则会在当前集合的末尾添加与当前集合中最后一个系列具有相同类型的额外系列。

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | 单元格数据范围公式。例如： "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

## 参见

* 类 [String](../../../system/string/)
* 类 [ChartData](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)