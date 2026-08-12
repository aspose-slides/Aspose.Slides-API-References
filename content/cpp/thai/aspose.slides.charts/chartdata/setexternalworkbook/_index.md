---
title: SetExternalWorkbook()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดไฟล์ทำงานภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ ข้อมูลแผนภูมิจะถูกอัปเดตจากไฟล์ทำงานเป้าหมาย.
type: docs
weight: 183
url: /th/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) เมธอด


กำหนดไฟล์ทำงานภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. [Chart](../../chart/) ข้อมูลจะถูกอัปเดตจากไฟล์ทำงานเป้าหมาย.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```


### อาร์กิวเม้นท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ทำงานเป้าหมาย |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) เมธอด


กำหนดไฟล์ทำงานภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```


### อาร์กิวเม้นท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | เส้นทางไปยังไฟล์ทำงานเป้าหมาย |
| updateChartData | **bool** | หากค่าคือ false จะอัปเดตเฉพาะเส้นทางไฟล์ทำงานเท่านั้น. [Chart](../../chart/) ข้อมูลจะไม่ถูกโหลดและอัปเดตจากไฟล์ทำงานเป้าหมาย. สามารถใช้ได้เมื่อไฟล์ทำงานเป้าหมายไม่มีอยู่หรือไม่พร้อมใช้งาน. หากค่าคือ true ข้อมูลแผนภูมิจะถูกอัปเดตจากไฟล์ทำงานเป้าหมาย. |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ChartData](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)