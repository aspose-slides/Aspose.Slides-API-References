---
title: ILoadOptions
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือฟอนต์เริ่มต้น) เมื่อโหลดงานนำเสนอ.
type: docs
weight: 2796
url: /th/aspose.slides/iloadoptions/
---
## ILoadOptions คลาส

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือฟอนต์เริ่มต้น) เมื่อโหลดงานนำเสนอ.

```cpp
class ILoadOptions : public virtual System::Object
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | แสดงถึงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มีจุดประสงค์เพื่อกำหนดอัตราการทำงาน/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | คืนค่าแบบอักษรเอเชียที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | คืนค่าแบบอักษรปกติที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | คืนค่าแบบอักษรสัญลักษณ์ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | คืนค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | กำหนดว่า [Aspose.Slides](../) จะลบวัตถุไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | ระบุแหล่งของแบบอักษรภายนอกที่จะใช้โดยงานนำเสนอ แบบอักษรเหล่านี้พร้อมใช้งานตลอดอายุงานของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น ๆ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | โทเคนเพื่อตรวจสอบการร้องขอการขัดจังหวะ. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | คืนค่าฟอร์แมตของงานนำเสนอที่จะโหลด อ่าน [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | คุณสมบัตินี้มีประโยชน์เมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่าจริงหมายถึงว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน ค่าผิดหมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้เข้ารหัสค่าคุณสมบัตินี้จะถูกละเว้นเสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าคุณสมบัตินี้เป็นจริง จะไม่สามารถโหลดคุณสมบัติของเอกสารและจะขว้างข้อยกเว้น อ่าน **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | รับรหัสผ่าน อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | คืนค่าอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก อ่าน [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | แสดงถึงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | คืนค่าอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานเทียบเคียงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เพื่อเปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นการทำงานเทียบเคียงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานเทียบเคียงของโอเปอร์เรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานเทียบเคียงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เพื่อเปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าด้วยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | แสดงถึงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มีจุดประสงค์เพื่อกำหนดอัตราการทำงาน/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | ตั้งค่าแบบอักษรเอเชียที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง เขียน [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งค่าแบบอักษรปกติที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง เขียน [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | ตั้งค่าแบบอักษรสัญลักษณ์ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง เขียน [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | ตั้งค่าภาษาเริ่มต้นสำหรับข้อความในงานนำเสนอ เขียน [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | กำหนดว่า [Aspose.Slides](../) จะลบวัตถุไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | ระบุแหล่งของแบบอักษรภายนอกที่จะใช้โดยงานนำเสนอ แบบอักษรเหล่านี้พร้อมใช้งานตลอดอายุงานของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น ๆ |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | โทเคนเพื่อตรวจสอบการร้องขอการขัดจังหวะ. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | ตั้งค่าฟอร์แมตของงานนำเสนอที่จะโหลด เขียน [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | คุณสมบัตินี้มีประโยชน์เมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่าจริงหมายถึงว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน ค่าผิดหมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้เข้ารหัสค่าคุณสมบัตินี้จะถูกละเว้นเสมอ หากคุณสมบัติของเอกสารในไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าคุณสมบัตินี้เป็นจริง จะไม่สามารถโหลดคุณสมบัติของเอกสารและจะขว้างข้อยกเว้น เขียน **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | ตั้งค่ารหัสผ่าน เขียน [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | ตั้งค่าอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก เขียน [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | แสดงถึงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งค่าอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) เพื่อให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานเทียบเคียงของเมธอด C# [Object.ToString()](../../system/object/tostring/) เพื่อเปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)