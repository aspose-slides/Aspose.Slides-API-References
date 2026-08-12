---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้กับงานนำเสนอ ฟอนต์เหล่านี้จะพร้อมใช้งานตลอดอายุของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น ๆ
type: docs
weight: 222
url: /th/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) เมธอด

ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้กับงานนำเสนอ ฟอนต์เหล่านี้จะพร้อมใช้งานตลอดอายุของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น ๆ

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีระบุฟอนต์ที่กำหนดเองที่ใช้กับ PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// ทำงานกับงานนำเสนอ
// CustomFont1, CustomFont2 รวมถึงฟอนต์จากโฟลเดอร์ assets\fonts & global\fonts และโฟลเดอร์ย่อยของมันสามารถใช้ได้กับงานนำเสนอ
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSources](../../ifontsources/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)