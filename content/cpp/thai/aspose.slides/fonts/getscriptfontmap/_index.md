---
title: GetScriptFontMap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนพจนานุกรมของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ
type: docs
weight: 79
url: /th/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() เมธอด

ส่งคืนพจนานุกรมของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```

### ค่าที่ส่งกลับ

พจนานุกรมที่แมปรหัสสคริปต์ไปยังชื่อฟอนต์

## หมายเหตุ

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [String](../../../system/string/)
* คลาส [Fonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)