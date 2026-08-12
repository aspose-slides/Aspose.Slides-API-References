---
title: set_Overlap()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D โดยเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%).
type: docs
weight: 196
url: /th/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) เมธอด

ระบุว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D โดยเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## หมายเหตุ

* -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์)  
* 0%: บาร์ถูกวางข้างกันโดยไม่มีการทับหรือระยะห่าง  
* 100%: การทับสูงสุด (บาร์ทับกันอย่างสมบูรณ์) คุณสมบัตินี้เป็นการอ่าน/เขียน **int8_t**  

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการทับสำหรับกลุ่มซีรีส์ของแผนภูมิและเรนเดอร์แผนภูมิที่ได้บนฟอร์ม:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ตั้งค่าการทับเป็น 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## ดูเพิ่มเติม

* คลาส [IChartSeriesGroup](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)