---
title: set_Overlap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่าบาร์และคอลัมน์จะทับซ้อนกันบนแผนภูมิ 2 มิติ มากเท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%).
type: docs
weight: 170
url: /th/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) เมธอด

ระบุว่าบาร์และคอลัมน์จะทับซ้อนกันบนแผนภูมิ 2 มิติ มากเท่าใดเป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## หมายเหตุ

* -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์)
* 0%: บาร์วางเคียงข้างกันโดยไม่มีการทับซ้อนหรือช่องว่าง
* 100%: การทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณสมบัตินี้เป็น read/write **int8_t**

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการทับซ้อนสำหรับกลุ่มซีรีส์แผนภูมิและแสดงแผนภูมิผลลัพธ์บนฟอร์ม: 
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

* คลาส [ChartSeriesGroup](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)