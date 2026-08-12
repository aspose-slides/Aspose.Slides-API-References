---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากแหล่งข้อมูลสำหรับแผนภูมิคือไฟล์งานภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ
type: docs
weight: 40
url: /th/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) เมธอด

หากแหล่งข้อมูลสำหรับแผนภูมิเป็นไฟล์งานภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
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