---
title: CalculateFormulas()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คำนวณสูตรทั้งหมดใน workbook และอัปเดตค่าของเซลล์ที่สอดคล้องกัน.
type: docs
weight: 14
url: /th/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() เมธอด


คำนวณสูตรทั้งหมดใน workbook และอัปเดตค่าของเซลล์ที่สอดคล้องกัน.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## หมายเหตุ



ตัวอย่างแสดงวิธีการกำหนดสูตรให้กับเซลล์และคำนวณค่าผลลัพธ์ ค่าในเซลล์ \"B4\" จะถูกกำหนดเป็น 5. 
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

* คลาส [IChartDataWorkbook](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)