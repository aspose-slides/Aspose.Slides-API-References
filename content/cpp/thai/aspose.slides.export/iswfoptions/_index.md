---
title: ISwfOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ SWF
type: docs
weight: 469
url: /th/aspose.slides.export/iswfoptions/
---
## ISwfOptions คลาส

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงตามสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่า ตามสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **bool** [get_Compressed](./get_compressed/)() | ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างหรือไม่ ค่าเริ่มต้นคือ **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | เปิด/ปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | คืนค่าสไตล์การแสดงผลของการไล่สี อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | ระบุคุณภาพของภาพ JPEG. \n\n ค่าเริ่มต้นคือ 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | ภาพที่จะปรากฏเป็นโลโก้ที่มุมบนขวาของตัวดู. \n\n ภาพควรเป็น PNG ขนาด 32x64 พิกเซล หากไม่เช่นนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | รับที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้ มีผลเฉพาะเมื่อมีการระบุ [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | แสดงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | แสดง/ซ่อนแผงด้านล่าง สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | แสดง/ซ่อนปุ่มเต็มจอ สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | ระบุว่าข้อเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | แสดง/ซ่อนแผงซ้าย สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | ระบุว่าควรแสดงกรอบรอบหน้า หรือไม่ ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | แสดง/ซ่อนตัวควบคุมการเปลี่ยนหน้า สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | แสดง/ซ่อนส่วนค้นหา สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | แสดง/ซ่อนแผงบนทั้งหมด สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกการนำเสนอหรือไม่ อ่าน **bool**. ค่าปริยายคือ **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | รับโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจ็กต์ที่มีประเภท **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่ สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | ระบุว่าควรรวมตัวดูเอกสารแบบบูรณาการในเอกสาร SWF ที่สร้างหรือไม่ ค่าเริ่มต้นคือ **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | คืนค่าอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างหรือไม่ ค่าเริ่มต้นคือ **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งค่าแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นทาง เขียน [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | เปิด/ปิดเมนูบริบท ค่าเริ่มต้นคือ true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งค่าสไตล์การแสดงผลของการไล่สี เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | ระบุคุณภาพของภาพ JPEG. \n\n ค่าเริ่มต้นคือ 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ภาพที่จะปรากฏเป็นโลโก้ที่มุมบนขวาของตัวดู. \n\n ภาพควรเป็น PNG ขนาด 32x64 พิกเซล หากไม่เช่นนั้นโลโก้อาจแสดงไม่ถูกต้อง. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | ตั้งค่าที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้ มีผลเฉพาะเมื่อมีการระบุ [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | แสดงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | แสดง/ซ่อนแผงด้านล่าง สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | แสดง/ซ่อนปุ่มเต็มจอ สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | แสดง/ซ่อนแผงซ้าย สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | ระบุว่าควรแสดงกรอบรอบหน้า หรือไม่ ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | แสดง/ซ่อนตัวควบคุมการเปลี่ยนหน้า สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | แสดง/ซ่อนส่วนค้นหา สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | แสดง/ซ่อนแผงบนทั้งหมด สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกการนำเสนอหรือไม่ เขียน **bool**. ค่าปริยายคือ **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | ตั้งค่าโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจ็กต์ที่มีประเภท **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่ สามารถแทนที่ได้ใน flashvars ค่าเริ่มต้นคือ false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | ระบุว่าควรรวมตัวดูเอกสารแบบบูรณาการในเอกสาร SWF ที่สร้างหรือไม่ ค่าเริ่มต้นคือ **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ISaveOptions](../isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)