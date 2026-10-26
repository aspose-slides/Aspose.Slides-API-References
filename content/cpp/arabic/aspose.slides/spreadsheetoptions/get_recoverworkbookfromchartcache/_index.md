---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides لـ C++ مرجع API
description: إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.
type: docs
weight: 27
url: /ar/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() طريقة

إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يتوفر، فسيتم استعادته من ذاكرة التخزين المؤقت للمخطط.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

* الفئة [SpreadsheetOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)