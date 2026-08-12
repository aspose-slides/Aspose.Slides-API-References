---
title: IVideoPlayerHtmlController
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML
type: docs
weight: 508
url: /th/aspose.slides.export/ivideoplayerhtmlcontroller/
---
## IVideoPlayerHtmlController คลาส


คลาสนี้อนุญาตให้ส่งออกไฟล์วิดีโอและเสียงเป็น HTML

```cpp
class IVideoPlayerHtmlController : public Aspose::Slides::Export::IHtmlFormattingController,
                                   public Aspose::Slides::Export::ISvgShapeFormattingController,
                                   public Aspose::Slides::Export::ILinkEmbedController
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| virtual void [FormatShape](../isvgshapeformattingcontroller/formatshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShape](../isvgshape/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | ฟังก์ชันนี้ถูกเรียกก่อนการเรนเดอร์รูปทรงเป็น SVG เพื่อให้ผู้ใช้ควบคุม SVG ที่ได้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนล็กของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual [LinkEmbedDecision](../linkembeddecision/) [GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/), [System::String](../../system/string/), [System::String](../../system/string/)) | กำหนดตำแหน่งที่อ็อบเจกต์ควรจะถูกจัดเก็บ เมธอดนี้ถูกเรียกหนึ่งครั้งต่อแต่ละ ID ของอ็อบเจกต์ ไม่รับประกันว่าจะไม่มีอ็อบเจกต์สองอันที่มีข้อมูลเดียวกัน semanticName และ contentType แต่มี ID ที่แตกต่างกัน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ เป็นอะแนล็กของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::String](../../system/string/) [GetUrl](../ilinkembedcontroller/geturl/)(**int32_t**, **int32_t**) | คืนค่า URL ไปยังอ็อบเจกต์ภายนอก เมธอดนี้จะถูกเรียกเสมอหาก [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) คืนค่า [LinkEmbedDecision::Link](../linkembeddecision/) และอาจถูกเรียกหาก [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) คืนค่า [LinkEmbedDecision::Embed](../linkembeddecision/) แต่ไม่สามารถฝังได้ สามารถเรียกหลายครั้งสำหรับ ID ของอ็อบเจกต์เดียวกัน. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ เป็นอะแนล็กของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ [LockContext](../../system/lockcontext/) วัตถุ sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนล็กของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถทำการโคลนชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เตรียมโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SaveExternal](../ilinkembedcontroller/saveexternal/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | บันทึกอ็อบเจกต์ภายนอก. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนล็กของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ [LockContext](../../system/lockcontext/) วัตถุ sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual void [WriteDocumentEnd](../ihtmlformattingcontroller/writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | ถูกเรียกเพื่อเขียนส่วนท้ายของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชัน. |
| virtual void [WriteDocumentStart](../ihtmlformattingcontroller/writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | ถูกเรียกเพื่อเขียนส่วนหัวของเอกสาร html. ถูกเรียกหนึ่งครั้งต่อการแปลงพรีเซนเทชัน. |
| virtual void [WriteShapeEnd](../ihtmlformattingcontroller/writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | ถูกเรียกก่อนการเรนเดอร์รูปทรง ถูกเรียกหนึ่งครั้งต่อแต่ละรูปทรง หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า. |
| virtual void [WriteShapeStart](../ihtmlformattingcontroller/writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | ถูกเรียกก่อนการเรนเดอร์รูปทรง ถูกเรียกหนึ่งครั้งต่อแต่ละรูปทรง หากฟังก์ชันนี้เขียนอะไรลงใน generator การสร้างภาพสไลด์ปัจจุบันจะเสร็จสิ้น ส่วน html ที่เพิ่มจะถูกแทรกและภาพใหม่จะเริ่มต้นบนภาพก่อนหน้า. |
| virtual void [WriteSlideEnd](../ihtmlformattingcontroller/writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | ถูกเรียกเพื่อเขียนส่วนท้ายของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์. |
| virtual void [WriteSlideStart](../ihtmlformattingcontroller/writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | ถูกเรียกเพื่อเขียนส่วนหัวของสไลด์ html. ถูกเรียกหนึ่งครั้งต่อแต่ละสไลด์. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IHtmlFormattingController](../ihtmlformattingcontroller/)
* คลาส [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)
* คลาส [ILinkEmbedController](../ilinkembedcontroller/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)