---
title: get_IsVisible()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: False หมายถึงป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (และดังนั้นทุก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false) มีค่าเป็นแบบอ่านอย่างเดียว bool.
type: docs
weight: 27
url: /th/aspose.slides.charts/idatalabelcollection/get_isvisible/
---
## IDataLabelCollection::get_IsVisible() เมธอด

False หมายถึงป้ายข้อมูลไม่ปรากฏตามค่าเริ่มต้น (และดังนั้นทุก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false) อ่านอย่างเดียว **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelCollection::get_IsVisible()=0
```

## หมายเหตุ

หากป้ายข้อมูลแสดงตามค่าเริ่มต้น คุณสามารถทำให้มันซ่อนตามค่าเริ่มต้นด้วยเมธอด [Hide()](../hide/). แต่หากป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ป้ายข้อมูล "visible 
by default" โดยการตั้งค่า Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true.

## ดูเพิ่มเติม

* คลาส [IDataLabelCollection](../)
* เนมสเปซ [Aspose::Slides::Charts](../../)
* ไลบรารี [Aspose.Slides](../../../)