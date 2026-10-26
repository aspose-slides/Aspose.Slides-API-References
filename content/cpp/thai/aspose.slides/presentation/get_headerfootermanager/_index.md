---
title: get_HeaderFooterManager()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API C++
description: ส่งคืนตัวจัดการ HeaderFooter จริง. อ่านอย่างเดียว IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /th/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() เมธอด

ส่งคืนตัวจัดการ HeaderFooter จริง. อ่านอย่างเดียว [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการมองเห็นส่วนท้ายภายใน [Slide](../../slide/) ของ PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// คุณสมบัติ IsFooterVisible ใช้เพื่อบ่งชี้ว่าตัวจับตำแหน่งส่วนท้ายของสไลด์ไม่มีอยู่
if (!headerFooterManager->get_IsFooterVisible())
{
    // เมธอด SetFooterVisibility ใช้เพื่อทำให้ตัวจับตำแหน่งส่วนท้ายของสไลด์ปรากฏ
    headerFooterManager->SetFooterVisibility(true);
}

// คุณสมบัติ IsSlideNumberVisible ใช้เพื่อบ่งชี้ว่าตัวจับตำแหน่งเลขหน้าของสไลด์ไม่มีอยู่
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // เมธอด SetSlideNumberVisibility ใช้เพื่อทำให้ตัวจับตำแหน่งเลขหน้าของสไลด์ปรากฏ
    headerFooterManager->SetSlideNumberVisibility(true);
}

// คุณสมบัติ IsDateTimeVisible ใช้เพื่อบ่งชี้ว่าตัวจับตำแหน่งวันเวลาในสไลด์ไม่มีอยู่
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // เมธอด SetFooterVisibility ใช้เพื่อทำให้ตัวจับตำแหน่งวันเวลาในสไลด์ปรากฏ
    headerFooterManager->SetDateTimeVisibility(true);
}

// เมธอด SetFooterText ใช้เพื่อกำหนดข้อความให้กับตัวจับตำแหน่งส่วนท้ายของสไลด์
headerFooterManager->SetFooterText(u"Footer text");
// เมธอด SetDateTimeText ใช้เพื่อกำหนดข้อความให้กับตัวจับตำแหน่งวันเวลาในสไลด์
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการมองเห็นส่วนท้ายลูกภายใน [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// เมธอด SetFooterAndChildFootersVisibility ใช้เพื่อทำให้สไลด์มาสเตอร์และตัวจับตำแหน่งส่วนท้ายของลูกทั้งหมดปรากฏ.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// เมธอด SetSlideNumberAndChildSlideNumbersVisibility ใช้เพื่อทำให้สไลด์มาสเตอร์และตัวจับตำแหน่งเลขหน้าของลูกทั้งหมดปรากฏ.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// เมธอด SetDateTimeAndChildDateTimesVisibility ใช้เพื่อทำให้สไลด์มาสเตอร์และตัวจับตำแหน่งวันเวลาของลูกทั้งหมดปรากฏ.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// เมธอด SetFooterAndChildFootersText ใช้เพื่อกำหนดข้อความให้กับสไลด์มาสเตอร์และตัวจับตำแหน่งส่วนท้ายของลูกทั้งหมด.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// เมธอด SetDateTimeAndChildDateTimesText ใช้เพื่อกำหนดข้อความให้กับสไลด์มาสเตอร์และตัวจับตำแหน่งวันเวลาของลูกทั้งหมด.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)