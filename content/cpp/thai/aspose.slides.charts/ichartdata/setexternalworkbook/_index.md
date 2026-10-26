---
title: SetExternalWorkbook()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูลแผนภูมิจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย.
type: docs
weight: 196
url: /th/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) เมธอด

กำหนดเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. [Chart](../../chart/) ข้อมูลจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | เส้นทางไปยังเวิร์กบุ๊กเป้าหมาย |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) เมธอด

กำหนดเวิร์กบุ๊กภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | เส้นทางไปยังเวิร์กบุ๊กเป้าหมาย |
| updateChartData | **bool** | หากค่าเป็น false จะอัปเดตเฉพาะเส้นทางเวิร์กบุ๊กเท่านั้น. [Chart](../../chart/) ข้อมูลจะไม่ถูกโหลดและอัปเดตจากเวิร์กบุ๊กเป้าหมาย. สามารถใช้ได้เมื่อเวิร์กบุ๊กเป้าหมายไม่มีอยู่หรือไม่พร้อมใช้งาน. หากค่าเป็น true ข้อมูลแผนภูมิจะได้รับการอัปเดตจากเวิร์กบุ๊กเป้าหมาย. |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)