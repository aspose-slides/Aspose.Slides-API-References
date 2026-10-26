---
title: GetScriptFontMap()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คืนพจนานุกรมของการกำหนดแบบอักษรสคริปต์ทั้งหมดในงานนำเสนอ.
type: docs
weight: 79
url: /th/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() เมธอด

ส่งคืนพจนานุกรมของการกำหนดแบบอักษรสคริปต์ทั้งหมดในงานนำเสนอ.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### ค่าที่ส่งกลับ

พจนานุกรมที่แมพรหัสสคริปต์เป็นชื่อแบบอักษร.

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
* คลาส [IFonts](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)