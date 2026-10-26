---
title: ISVGOptions
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แสดงตัวเลือก SVG.
type: docs
weight: 404
url: /th/aspose.slides.export/isvgoptions/
---
## ISVGOptions คลาส

Represents an SVG options.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/) |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | ธงบูลีนบ่งชี้ว่าชิ้นส่วนที่ถูกตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น **true** ชิ้นส่วนที่ถูกตัดจะถูกลบ หากเป็น **false** จะถูกทำซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน **bool** |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ อ่าน **bool** |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | รับค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิกเจอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ ตามค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false** |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | ปิดการแยกกราเดียน FromCornerX และ FromCenter อ่าน **bool** |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 ไม่มีความสามารถในการกำหนดช่องระยะสำหรับมาร์คเกอร์ [Aspose.Slides](../../aspose.slides/) เอนจิ้นการเขียน SVG มีวิธีแก้ปัญหานี้: มันตัดส่วนท้ายของเส้นที่มีลูกศรให้อยู่ ไม่ให้เส้นทับกับมาร์คเกอร์ ตัวเลือกนี้จะปิดพฤติกรรมดังกล่าว อ่าน **bool** |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | กำหนดวิธีการจัดการแบบอักษรที่โหลดจากภายนอก อ่าน [SvgExternalFontsHandling](../svgexternalfontshandling/) |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | คืนสไตล์ภาพของกราเดียน อ่าน [GradientStyle](../../aspose.slides/gradientstyle/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | ให้ตัวเลือกที่ควบคุมลักษณะของอ็อบเจกต์ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่าน-อย่างเดียว [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | กำหนดคุณภาพการเข้ารหัส JPEG อ่าน **int32_t** |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | คืนค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟาไลน์ อ่าน **int32_t** |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | แสดงระดับการบีบอัดภาพ อ่าน [PicturesCompression](../picturescompression/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | แสดงอ็อบเจกต์คอลแบ็กสำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | รับและตั้งค่าหน้าต่างคอลแบ็กที่ให้ผู้ใช้ควบคุมการแปลงรูปทรง อ่าน [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน **bool** ค่าเริ่มต้นคือ **false** |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่ อ่าน **bool** ค่าเริ่มต้นคือ true |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | กำหนดว่าจะรวมเฟรมข้อความในพื้นที่เรนเดอร์หรือไม่ อ่าน **bool** ค่าเริ่มต้นคือ false |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | คืนอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ อนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ อนาล็อกของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/) |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | ธงบูลีนบ่งชี้ว่าชิ้นส่วนที่ถูกตัดยังคงเป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็น **true** ชิ้นส่วนที่ถูกตัดจะถูกลบ หากเป็น **false** จะถูกทำซีเรียลไลซ์ในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) เขียน **bool** |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | กำหนดว่าข้อความ 3D ถูกปิดใช้งานใน SVG หรือไม่ เขียน **bool** |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิกเจอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ ตามค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false** |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | ปิดการแยกกราเดียน FromCornerX และ FromCenter เขียน **bool** |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 ไม่มีความสามารถในการกำหนดช่องระยะสำหรับมาร์คเกอร์ [Aspose.Slides](../../aspose.slides/) เอนจิ้นการเขียน SVG มีวิธีแก้ปัญหานี้: มันตัดส่วนท้ายของเส้นที่มีลูกศรให้อยู่ ไม่ให้เส้นทับกับมาร์คเกอร์ ตัวเลือกนี้จะปิดพฤติกรรมดังกล่าว เขียน **bool** |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | กำหนดวิธีการจัดการแบบอักษรที่โหลดจากภายนอก เขียน [SvgExternalFontsHandling](../svgexternalfontshandling/) |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งค่าสไตล์ภาพของกราเดียน เขียน [GradientStyle](../../aspose.slides/gradientstyle/) |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | กำหนดคุณภาพการเข้ารหัส JPEG เขียน **int32_t** |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไทซ์เมตาฟาไลน์ เขียน **int32_t** |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | แสดงระดับการบีบอัดภาพ เขียน [PicturesCompression](../picturescompression/) |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | แสดงอ็อบเจกต์คอลแบ็กสำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | รับและตั้งค่าหน้าต่างคอลแบ็กที่ให้ผู้ใช้ควบคุมการแปลงรูปทรง เขียน [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | ระบุว่าควรข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ เขียน **bool** ค่าเริ่มต้นคือ **false** |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | กำหนดว่าจะทำการหมุนรูปทรงตามที่ระบุขณะเรนเดอร์หรือไม่ เขียน **bool** ค่าเริ่มต้นคือ true |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | กำหนดว่าจะรวมเฟรมข้อความในพื้นที่เรนเดอร์หรือไม่ เขียน **bool** ค่าเริ่มต้นคือ false |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่ เขียน **bool** |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งค่าอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอากิวเมนต์เทมเพลตลำดับที่ n เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ISaveOptions](../isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)