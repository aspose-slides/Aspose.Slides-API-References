---
title: set_RecoverWorkbookFromChartCache()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان مصدر البيانات للمخطط مصنفًا خارجيًا ولم يكن متاحًا، فسيتم استرجاعه من ذاكرة مخزن المخطط المؤقتة.
type: docs
weight: 40
url: /ar/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) طريقة

إذا كان مصدر البيانات للمخطط هو مصنف خارجي ولم يكن متاحًا، فسيتم استرداده من ذاكرة مخزن المخطط المؤقتة.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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

* فئة [SpreadsheetOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)