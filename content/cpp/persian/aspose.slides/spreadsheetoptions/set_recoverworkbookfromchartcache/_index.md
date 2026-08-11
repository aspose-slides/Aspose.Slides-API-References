---
title: set_RecoverWorkbookFromChartCache()
second_title: مرجع API Aspose.Slides برای C++
description: اگر منبع داده برای نمودار یک کاربرگ خارجی باشد و در دسترس نباشد، از حافظه نهان نمودار بازیابی می‌شود.
type: docs
weight: 40
url: /fa/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) متد

اگر منبع داده برای نمودار یک کاربرگ خارجی باشد و در دسترس نباشد، از حافظه نهان نمودار بازیابی می‌شود.

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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