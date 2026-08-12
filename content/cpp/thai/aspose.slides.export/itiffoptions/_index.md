---
title: ITiffOptions
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF.
type: docs
weight: 495
url: /th/aspose.slides.export/itiffoptions/
---
## ITiffOptions คลาส

Provides options that control how a presentation is saved in TIFF format.

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ค่า NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ค่า NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | กำหนดอัลกอริทึมสำหรับแปลงภาพสีเป็นภาพสีขาว-ดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [ITiffOptions::get_CompressionType()](./get_compressiontype/) ถูกตั้งเป็น [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) อ่าน [BlackWhiteConversionMode](../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | กำหนดประเภทการบีบอัด อ่าน [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | กำหนดความละเอียดแนวนอนเป็น จุดต่อ นิ้ว อ่าน **uint32_t**. |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | กำหนดความละเอียดแนวตั้งเป็น จุดต่อ นิ้ว อ่าน **uint32_t**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | คืนค่ารูปแบบการแสดงผลของการไล่สี อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | กำหนดขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างขึ้นจะคำนวณตามค่าขนาดสไลด์ของการนำเสนอ อ่าน [System::Drawing::Size](../../system.drawing/size/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | ให้ตัวเลือกที่ควบคุมลักษณะการแสดงของอ็อบเจ็กต์ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | กำหนดรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น อ่าน [ImagePixelFormat](../imagepixelformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | กำหนดว่าหนังสือเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | กำหนดว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | รับโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | คืนอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นสอดคล้องกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการทำแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ สอดคล้องกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType สอดคล้องกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | สอดคล้องกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการทำสำเนาประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ค่าประเภทกับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เฉพาะกรณีของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับสตリング. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | กำหนดอัลกอริทึมสำหรับแปลงภาพสีเป็นภาพสีขาว-ดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [ITiffOptions::get_CompressionType()](./get_compressiontype/) ถูกตั้งเป็น [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) เขียน [BlackWhiteConversionMode](../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | กำหนดประเภทการบีบอัด เขียน [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/). |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | กำหนดความละเอียดแนวนอนเป็น จุดต่อ นิ้ว เขียน **uint32_t**. |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | กำหนดความละเอียดแนวตั้งเป็น จุดต่อ นิ้ว เขียน **uint32_t**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งรูปแบบการแสดงผลของการไล่สี เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | กำหนดขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างขึ้นจะคำนวณตามค่าขนาดสไลด์ของการนำเสนอ เขียน [System::Drawing::Size](../../system.drawing/size/). |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | กำหนดรูปแบบพิกเซลสำหรับภาพที่สร้างขึ้น เขียน [ImagePixelFormat](../imagepixelformat/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | กำหนดว่าหนังสือเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนหรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | กำหนดว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | ตั้งโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | สอดคล้องกับเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ISaveOptions](../isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)