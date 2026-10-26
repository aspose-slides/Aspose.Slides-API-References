---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: หากแหล่งข้อมูลของแผนภูมิเป็นเวิร์กบุ๊กภายนอกและไม่สามารถใช้ได้ ระบบจะกู้คืนจากแคชของแผนภูมิ
type: docs
weight: 40
url: /th/aspose.slides/spreadsheetoptions/set_recoverworkbookfromchartcache/
---
## SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) เมธอด


หากแหล่งข้อมูลสำหรับแผนภูมิเป็นหนังสืองานภายนอกและไม่สามารถใช้ได้ ระบบจะกู้คืนจากแคชของแผนภูมิ

```cpp
void Aspose::Slides::SpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value) override
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
* Library [Aspose.Slides](../../../)