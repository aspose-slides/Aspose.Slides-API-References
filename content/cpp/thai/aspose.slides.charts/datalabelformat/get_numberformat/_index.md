---
title: get_NumberFormat()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "เป็นสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน System::String."
type: docs
weight: 27
url: /th/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() เมธอด


เป็นสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## หมายเหตุ



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



หากพาเรนต์ของวัตถุ [DataLabelFormat](../) นี้เป็นคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) ของป้ายข้อมูล, แล้วคุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/). เมื่อกำหนดคุณสมบัตินี้ด้วยค่า ค่านั้นจะถูกกำหนดให้กับคุณสมบัติ NumberFormat สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน [DataLabelCollection](../../datalabelcollection/) ด้วย (เช่น \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" ทำให้ DataLabels[i].NumberFormat ทั้งหมดเท่ากับ val). 


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [DataLabelFormat](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)