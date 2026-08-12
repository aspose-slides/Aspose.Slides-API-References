---
title: get_FontsManager()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนตัวจัดการแบบอักษร. อ่านอย่างเดียว IFontsManager.
type: docs
weight: 157
url: /th/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() เมธอด


ส่งคืนตัวจัดการแบบอักษร. อ่านอย่างเดียว [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มแบบอักษรฝังไว้ใน PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```




## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontsManager](../../ifontsmanager/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)