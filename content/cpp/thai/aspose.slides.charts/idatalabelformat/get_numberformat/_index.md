---
title: get_NumberFormat()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "แทนสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน System::String."
type: docs
weight: 27
url: /th/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() เมธอด

แทนสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels. อ่าน [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## หมายเหตุ

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

ถ้าพาเรนต์ของอ็อบเจกต์ [DataLabelFormat](../../datalabelformat/) นี้เป็นคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) ของป้ายข้อมูล, แล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/). เมื่อคุณสมบัตินี้ถูกกำหนดด้วยค่า, ค่านั้นจะถูกกำหนดสำหรับคุณสมบัติ NumberFormat ของป้ายข้อมูลทั้งหมดในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) (เช่น "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" ทำให้ DataLabels[i].NumberFormat ทั้งหมดเท่ากับ val).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IDataLabelFormat](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)