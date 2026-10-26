---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากแหล่งข้อมูลของแผนภูมิมาจาก workbook ภายนอกและไม่สามารถใช้งานได้ จะทำการกู้คืนจากแคชของแผนภูมิ
type: docs
weight: 27
url: /th/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() เมธอด


หากแหล่งข้อมูลสำหรับแผนภูมิเกิดจาก workbook ภายนอกและไม่สามารถใช้ได้ จะทำการกู้คืนจากแคชของแผนภูมิ

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```

## หมายเหตุ



ตัวอย่าง:
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## ดูเพิ่มเติม

* คลาส [ISpreadsheetOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)