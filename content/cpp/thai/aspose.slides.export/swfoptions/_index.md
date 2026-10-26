---
title: SwfOptions
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานพรีเซนเทชันเป็นรูปแบบ Swf.
type: docs
weight: 742
url: /th/aspose.slides.export/swfoptions/
---
## SwfOptions คลาส


ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานพรีเซนเทชันเป็นรูปแบบ Swf

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้สำนวน C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| **bool** [get_Compressed](./get_compressed/)() override | ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ ค่าเริ่มต้นคือ **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | เปิดหรือปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | คืนค่าสไตล์ภาพแบบไล่สีของกรเดียนท์ อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | ระบุคุณภาพของภาพ JPEG ค่าเริ่มต้นคือ 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | ภาพที่จะแสดงเป็นโลโก้ที่มุมบนขวาของผู้ชม ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | รับที่อยู่ไฮเปอร์ลิงก์เต็มของโลโก้ จะมีผลก็ต่อเมื่อกำหนด [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | เป็นอ็อบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | แสดง/ซ่อนแผงล่าง สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | แสดง/ซ่อนปุ่มเต็มจอ สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | แสดง/ซ่อนแผงซ้าย สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | ระบุว่าควรแสดงกรอบรอบหน้าเบจหรือไม่ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | แสดง/ซ่อนตัวควบคุมการเปลี่ยนหน้า สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | แสดง/ซ่อนส่วนค้นหา สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | แสดง/ซ่อนแผงบนทั้งหมด สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อตอนบันทึกพรีเซนเทชัน อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | รับโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกพรีเซนเทชัน [ISlidesLayoutOptions](../islideslayoutoptions/) คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ประเภท [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่ สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | ระบุว่าเอกสาร SWF ที่สร้างควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่ ค่าเริ่มต้นคือ **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | คืนค่าหรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจกต์ เป็นฟังก์ชันคล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ฟังก์ชันคล้ายกับเครื่องหมาย 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ ค่าเริ่มต้นคือ **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | เปิดหรือปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์ภาพแบบไล่สีของกรเดียนท์ เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | ระบุคุณภาพของภาพ JPEG ค่าเริ่มต้นคือ 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ภาพที่จะแสดงเป็นโลโก้ที่มุมบนขวาของผู้ชม ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | ตั้งค่าที่อยู่ไฮเปอร์ลิงก์เต็มของโลโก้ จะมีผลก็ต่อเมื่อกำหนด [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | เป็นอ็อบเจกต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | แสดง/ซ่อนแผงล่าง สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | แสดง/ซ่อนปุ่มเต็มจอ สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | แสดง/ซ่อนแผงซ้าย สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | ระบุว่าควรแสดงกรอบรอบหน้าเบจหรือไม่ ค่าเริ่มต้นคือ true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | แสดง/ซ่อนตัวควบคุมการเปลี่ยนหน้า สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | แสดง/ซ่อนส่วนค้นหา สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | แสดง/ซ่อนแผงบนทั้งหมด สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อตอนบันทึกพรีเซนเทชัน เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | ตั้งค่าโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกพรีเซนเทชัน [ISlidesLayoutOptions](../islideslayoutoptions/) คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ประเภท [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่ สามารถกำหนดทับใน flashvars ได้ ค่าเริ่มต้นคือ false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | ระบุว่าเอกสาร SWF ที่สร้างควรรวมตัวดูเอกสารแบบบูรณาการหรือไม่ ค่าเริ่มต้นคือ **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | คืนค่าหรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าพารามิเตอร์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าจำนวนอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
|  [SwfOptions](./swfoptions/)() | คอนสตรัคเตอร์เริ่มต้น. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นฟังก์ชันคล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีการแปลง PowerPoint เป็น SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* คลาส [ISwfOptions](../iswfoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)