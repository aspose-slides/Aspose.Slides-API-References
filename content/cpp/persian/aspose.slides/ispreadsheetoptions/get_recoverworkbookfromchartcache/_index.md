---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر منبع داده برای نمودار یک کار-کتاب خارجی باشد و در دسترس نباشد، از کش نمودار بازیابی خواهد شد.
type: docs
weight: 27
url: /fa/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() متد

اگر منبع داده برای chart یک workbook خارجی باشد و در دسترس نباشد، از chart cache بازیابی خواهد شد.

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
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

## مراجع

* کلاس [ISpreadsheetOptions](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)