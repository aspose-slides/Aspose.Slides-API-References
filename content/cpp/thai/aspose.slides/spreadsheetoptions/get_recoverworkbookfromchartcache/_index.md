---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: หากแหล่งข้อมูลสำหรับแผนภูมิมาจากหนังสือทำงานภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ
type: docs
weight: 27
url: /th/aspose.slides/spreadsheetoptions/get_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::get_RecoverWorkbookFromChartCache() เมธอด


หากแหล่งข้อมูลสำหรับแผนภูมิมาจากหนังสือทำงานภายนอกและไม่สามารถเข้าถึงได้ จะทำการกู้คืนจากแคชของแผนภูมิ

```cpp
bool Aspose::Slides::SpreadsheetOptions::get_RecoverWorkbookFromChartCache() override
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

* คลาส [SpreadsheetOptions](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)