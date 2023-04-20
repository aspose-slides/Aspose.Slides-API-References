---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides for C++ API Reference
description: If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.
type: docs
weight: 40
url: /cpp/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) method


If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## Remarks



Example: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## See Also

* Class [ISpreadsheetOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)