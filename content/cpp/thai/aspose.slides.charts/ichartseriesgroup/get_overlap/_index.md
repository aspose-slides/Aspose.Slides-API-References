---
title: get_Overlap()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิ 2-D ในรูปเปอร์เซ็นต์ (จาก -100% ถึง 100%).
type: docs
weight: 183
url: /th/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() เมธอด

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิ 2-D ในรูปเปอร์เซ็นต์ (จาก -100% ถึง 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## หมายเหตุ

* -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์).
* 0%: บาร์จัดวางเคียงข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง.
* 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันอย่างสมบูรณ์). คุณสมบัตินี้อ่าน/เขียนได้ **int8_t**.

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการทับซ้อนสำหรับกลุ่มซีรีส์แผนภูมิและเรนเดอร์แผนภูมิที่ได้บนฟอร์ม: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ตั้งค่าการทับซ้อนเป็น 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## ดูเพิ่มเติม

* คลาส [IChartSeriesGroup](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)