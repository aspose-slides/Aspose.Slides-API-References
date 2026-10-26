---
title: get_Placeholder()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนตัวจัดตำแหน่งสำหรับรูปร่าง. ส่งคืนค่า null หากรูปทรงไม่มีตัวจัดตำแหน่ง. อ่านอย่างเดียว IPlaceholder.
type: docs
weight: 14
url: /th/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() method

ส่งคืนตัวจัดตำแหน่งสำหรับรูปร่าง ส่งคืนค่า null หากรูปทรงไม่มีตัวจัดตำแหน่ง อ่านอย่างเดียว [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## Remarks

ตัวอย่างต่อไปนี้แสดงวิธีเปลี่ยนข้อความใน [Placeholder](../../placeholder/).
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// Accesses the first slide
auto slide = pres->get_Slides()->idx_get(0);

// Iterates through shapes to find the placeholder
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // เปลี่ยนข้อความในแต่ละ placeholder
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// บันทึกงานนำเสนอไปยังดิสก์
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีตั้งค่า Prompt Text ใน [Placeholder](../../placeholder/).
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPlaceholder](../../iplaceholder/)
* คลาส [Shape](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)