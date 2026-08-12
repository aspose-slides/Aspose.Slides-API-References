---
title: CalculateFormulas()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คำนวณสูตรทั้งหมดในสมุดงานและอัปเดตค่าของเซลล์ที่เกี่ยวข้อง.
type: docs
weight: 53
url: /th/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() เมธอด


คำนวณสูตรทั้งหมดในสมุดงานและอัปเดตค่าของเซลล์ที่เกี่ยวข้อง.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## หมายเหตุ



ตัวอย่างแสดงวิธีกำหนดสูตรให้กับเซลล์และคำนวณค่า ค่าในเซลล์ \"B4\" จะถูกตั้งเป็น 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## ดูเพิ่มเติม

* คลาส [ChartDataWorkbook](../)
* เนมส페ซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)