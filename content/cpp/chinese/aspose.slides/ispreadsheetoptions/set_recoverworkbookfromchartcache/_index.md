---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides for C++ API 参考
description: 如果图表的数据源是外部工作簿且不可用，将从图表缓存中恢复。
type: docs
weight: 40
url: /zh/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) 方法

如果图表的数据源是外部工作簿且不可用，则会从图表缓存中恢复。

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## 备注


示例：
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## 另见

* 类 [ISpreadsheetOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)