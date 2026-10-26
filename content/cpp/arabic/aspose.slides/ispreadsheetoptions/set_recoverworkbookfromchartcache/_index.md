---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides لـ C++ مرجع API
description: إذا كان مصدر البيانات للمخطط هو دفتر عمل خارجي ولم يتوفر، فسيتم استرداده من ذاكرة التخزين المؤقت للمخطط.
type: docs
weight: 40
url: /ar/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) طريقة

إذا كان مصدر البيانات للمخطط هو دفتر عمل خارجي ولم يتوفر، فسيتم استرداده من ذاكرة التخزين المؤقت للمخطط.

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## ملاحظات



مثال: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## انظر أيضًا

* فئة [ISpreadsheetOptions](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)