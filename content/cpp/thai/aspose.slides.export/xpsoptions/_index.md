---
title: XpsOptions
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็นรูปแบบ XPS
type: docs
weight: 807
url: /th/aspose.slides.export/xpsoptions/
---
## XpsOptions คลาส

Provides options that control how a presentation is saved in XPS format.

```cpp
class XpsOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IXpsOptions
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้รูปแบบของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | คืนค่าแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | เป็นจริงเพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์ อ่าน **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | คืนค่าสไตล์การแสดงผลของการไล่สี อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | เป็นออบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | เป็นจริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG อ่าน **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | ระบุว่าหลักเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | คืนค่า หรือ ตั้งค่าออบเจกต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือจะถูกยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับออบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจกต์กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคัดลอกชนิดกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของออบเจกต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงร่วมตามค่าที่ระบุ. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าแบบอักษรที่ใช้เมื่อไม่พบแบบอักษรต้นทาง เขียน [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | เป็นจริงเพื่อวาดกรอบสีดำรอบสไลด์แต่ละสไลด์ เขียน **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์การแสดงผลของการไล่สี เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | เป็นออบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | เป็นจริงเพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG เขียน **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | ระบุว่าหลักเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | คืนค่า หรือ ตั้งค่าออบเจกต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจกต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
|  [XpsOptions](./xpsoptions/)() | คอนสตรัคเตอร์เริ่มต้น. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

The following example shows how to converting presentations to XPS using default settings. 
```cpp
// สร้างวัตถุ Presentation ที่แทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>(u"Convert_XPS.pptx");

// บันทึกงานนำเสนอเป็นเอกสาร XPS
pres->Save(u"XPS_Output_Without_XPSOption_out.xps", SaveFormat::Xps);
```
The following example shows how to converting presentations to XPS using custom settings. 
```cpp
// สร้างวัตถุ Presentation ที่แทนไฟล์งานนำเสนอ
auto pres = System::MakeObject<Presentation>(u"Convert_XPS_Options.pptx");

// สร้างอ็อบเจกต์ของคลาส TiffOptions
System::SharedPtr<XpsOptions> options = System::MakeObject<XpsOptions>();
// บันทึก MetaFiles เป็น PNG
options->set_SaveMetafilesAsPng(true);
// บันทึกงานนำเสนอเป็นเอกสาร XPS
pres->Save(u"XPS_With_Options_out.xps", SaveFormat::Xps, options);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* คลาส [IXpsOptions](../ixpsoptions/)
* เนมสเปส [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)