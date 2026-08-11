---  
title: get_RecoverWorkbookFromChartCache()  
second_title: Aspose.Slides برای C++ مرجع API  
description: اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی می‌شود.  
type: docs  
weight: 27  
url: /fa/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/  
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() متد


اگر منبع داده برای نمودار یک کتاب‌کار خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی می‌شود.

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
```

## توضیحات



مثال:
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## موارد مرتبط

* کلاس [SpreadsheetOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)