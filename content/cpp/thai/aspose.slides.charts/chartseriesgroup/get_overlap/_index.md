---
title: get_Overlap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันมากเท่าใดบนแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%).
type: docs
weight: 157
url: /th/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() เมธอด

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันมากเท่าใดบนแผนภูมิ 2-มิติ เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## หมายเหตุ

* -100%: ระยะห่างสูงสุด (บาร์แยกออกจากกันอย่างสมบูรณ์)
* 0%: บาร์จัดเรียงเคียงข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง
* 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด) คุณสมบัตินี้เป็นอ่าน/เขียน **int8_t**.

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการทับซ้อนสำหรับ chart series group และเรนเดอร์แผนภูมิที่ได้บนฟอร์ม: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ตั้งค่า overlap เป็น 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## ดูเพิ่มเติม

* คลาส [ChartSeriesGroup](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)