---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตั้งลิงก์ภายนอกเมื่อคลิก.
type: docs
weight: 1
url: /th/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) เมธอด


ตั้งลิงก์ภายนอกเมื่อคลิก.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเพิ่ม Text Box ด้วย [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// ดึงสไลด์แรกในงานนำเสนอ
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// เพิ่มอ็อบเจกต์ AutoShape โดยตั้งค่าชนิดเป็น Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// เข้าถึงคุณสมบัติ ITextFrame ที่เชื่อมโยงกับ AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// เพิ่มข้อความบางส่วนลงในเฟรม
portion->set_Text(u"Aspose.Slides");

// ตั้งค่า Hyperlink สำหรับข้อความส่วน
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// บันทึกงานนำเสนอ PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IHyperlink](../../ihyperlink/)
* คลาส [String](../../../system/string/)
* คลาส [HyperlinkManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)