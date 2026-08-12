---
title: GetFontName()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนชื่อแบบอักษร โดยแทนที่การอ้างอิงธีมด้วยแบบอักษรจริงที่ใช้งาน
type: docs
weight: 27
url: /th/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) เมธอด

คืนชื่อแบบอักษร โดยแทนที่การอ้างอิงธีมด้วยแบบอักษรที่ใช้งานจริง

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) ที่ควรใช้เพื่อดึงชื่อแบบอักษรตามธีม. ขึ้นอยู่กับผู้เรียกเพื่อให้ค่าเป็นค่าที่ถูกต้อง. ดู [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### ค่าที่คืน

ชื่อแบบอักษร.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* คลาส [FontData](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)