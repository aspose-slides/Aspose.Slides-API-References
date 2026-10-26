---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ระบุแหล่งที่มาของแบบอักษรภายนอกที่ใช้ในงานนำเสนอ แบบอักษรเหล่านี้จะพร้อมใช้งานตลอดอายุการใช้งานของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น
type: docs
weight: 209
url: /th/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() เมธอด

ระบุแหล่งที่มาของแบบอักษรภายนอกที่ใช้ในงานนำเสนอ แบบอักษรเหล่านี้จะพร้อมใช้งานตลอดอายุการใช้งานของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีระบุแบบอักษรที่กำหนดเองที่ใช้กับ PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// ทำงานกับงานนำเสนอ
// CustomFont1, CustomFont2 รวมถึงแบบอักษรจากโฟลเดอร์ assets\fonts & global\fonts และโฟลเดอร์ย่อยของมันสามารถใช้ได้ในงานนำเสนอ
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSources](../../ifontsources/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)