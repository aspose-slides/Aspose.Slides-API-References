---
title: set_NumberFormat()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แสดงถึงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. เขียน System::String."
type: docs
weight: 40
url: /th/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) เมธอด

แสดงถึงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. เขียน [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## หมายเหตุ

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

ถ้าพาเรนต์ของอ็อบเจกต์ [DataLabelFormat](../) นี้เป็นคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) ของป้ายข้อมูล, แล้วคุณสมบัตินี้จะรับหรือกำหนดค่าปริยายของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/). เมื่อคุณสมบัตินี้ถูกตั้งค่าด้วยค่าใดค่าหนึ่ง, ค่านั้นจะถูกตั้งค่าสำหรับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) (เช่น \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" ทำให้ DataLabels[i].NumberFormat มีค่าเท่ากับ val).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [DataLabelFormat](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)