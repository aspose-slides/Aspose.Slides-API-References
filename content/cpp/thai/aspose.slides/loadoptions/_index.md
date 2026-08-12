---
title: LoadOptions
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อนุญาตให้กำหนดตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือแบบอักษรเริ่มต้น) เมื่อโหลดงานนำเสนอ.
type: docs
weight: 4395
url: /th/aspose.slides/loadoptions/
---
## LoadOptions คลาส

Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าตามสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มีจุดประสงค์เพื่อกำหนดอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | คืนค่าแบบอักษรเอเชียที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | คืนค่าแบบอักษรธรรมดาที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | คืนค่าแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | คืนค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ อ่าน [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | กำหนดว่า [Aspose.Slides](../) จะลบอ็อบเจ็กต์ไบนารีที่ฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ แบบอักษรเหล่านี้มีให้ใช้งานตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | โทเค็นสำหรับตรวจสอบคำขอการหยุดชั่วคราว. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | คืนรูปแบบของงานนำเสนอที่จะโหลด อ่าน [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและละเว้นรหัสผ่าน ค่า false หมายความว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้ถูกเข้ารหัสค่าคุณสมบัติจะแม้แต่จะถูกละเว้น หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าคุณสมบัติเป็น true จะไม่สามารถโหลดคุณสมบัติของเอกสารได้และจะเกิดข้อยกเว้น อ่าน **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | รับรหัสผ่าน อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | คืนอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก อ่าน [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวณสูตรสำหรับแผนภูมิ |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | คืนอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่าจะดำเนินการโหลดต่อหรือยกเลิกอ่าน [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เทียบเคียงกับโอเปอร์เรเตอร์ 'is' ของ C# |
|  [LoadOptions](./loadoptions/)() | สร้างตัวเลือกการโหลดเริ่มต้นใหม่ |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | สร้างตัวเลือกการโหลดใหม่ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มีจุดประสงค์เพื่อกำหนดอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | กำหนดแบบอักษรเอเชียที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/) |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | กำหนดแบบอักษรธรรมดาที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/) |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | กำหนดแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/) |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | กำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ เขียน [System::String](../../system/string/) |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | กำหนดว่า [Aspose.Slides](../) จะลบอ็อบเจ็กต์ไบนารีที่ฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่ เขียน **bool** |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ แบบอักษรเหล่านี้มีให้ใช้งานตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น เขียน |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | โทเค็นสำหรับตรวจสอบคำขอการหยุดชั่วคราว |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | กำหนดรูปแบบของงานนำเสนอที่จะโหลด เขียน [Slides::LoadFormat](../loadformat/) |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและละเว้นรหัสผ่าน ค่า false หมายความว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้ถูกเข้ารหัสค่าคุณสมบัติจะแม้แต่จะถูกละเว้น หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าคุณสมบัติเป็น true จะไม่สามารถโหลดคุณสมบัติของเอกสารได้และจะเกิดข้อยกเว้น เขียน **bool** |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | กำหนดรหัสผ่าน เขียน [System::String](../../system/string/) |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | กำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก เขียน [IResourceLoadingCallback](../iresourceloadingcallback/) |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวณสูตรสำหรับแผนภูมิ |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่าจะดำเนินการโหลดต่อหรือยกเลิก เขียน [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) ให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้างโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ILoadOptions](../iloadoptions/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)