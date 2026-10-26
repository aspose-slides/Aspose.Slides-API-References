---
title: AddTextFrame()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่ม TextFrame ใหม่ให้กับรูปทรง หากรูปทรงมี TextFrame อยู่แล้วก็จะเปลี่ยนข้อความของมันเท่านั้น.
type: docs
weight: 66
url: /th/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) เมธอด


เพิ่ม [TextFrame](../../textframe/) ใหม่ให้กับรูปทรง หากรูปทรงมี [TextFrame](../../textframe/) อยู่แล้วก็จะเปลี่ยนข้อความของมันเท่านั้น.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Default text for a new [TextFrame](../../textframe/). |
## หมายเหตุ


The following sample code shows how to add watermark text in PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 The following example shows how to create Text Box on [Slide](../../slide/). 
```cpp
// สร้างอินสแตนซ์ Presentation
auto pres = System::MakeObject<Presentation>();

// ดึงสไลด์แรกใน Presentation
auto slide = pres->get_Slides()->idx_get(0);
// เพิ่ม AutoShape โดยกำหนดประเภทเป็น Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// เพิ่ม TextFrame ให้กับ Rectangle
shape->AddTextFrame(u" ");
// เข้าถึง TextFrame
auto txtFrame = shape->get_TextFrame();
// สร้างอ็อบเจ็กต์ Paragraph สำหรับ TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// สร้างอ็อบเจ็กต์ Portion สำหรับ Paragraph
auto portion = para->get_Portions()->idx_get(0);
// ตั้งค่าข้อความ
portion->set_Text(u"Aspose TextBox");
// บันทึก Presentation ลงดิสก์
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to add column in Text Box. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// ดึงสไลด์แรกในพรีเซนเทชัน
auto slide = presentation->get_Slides()->idx_get(0);
// Add an AutoShape with type set as Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Add TextFrame to the Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Gets the text format of TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Specifies the number of columns in TextFrame
format->set_ColumnCount(3);
// Specifies the spacing between columns
format->set_ColumnSpacing(10);
// Saves the presentation
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextFrame](../../itextframe/)
* คลาส [String](../../../system/string/)
* คลาส [AutoShape](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)