---
title: SVGOptions
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: เป็นตัวแทนของตัวเลือก SVG.
type: docs
weight: 703
url: /th/aspose.slides.export/svgoptions/
---
## SVGOptions คลาส

Represents an SVG options.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดเลย รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | คืนค่าการตั้งค่าเริ่มต้น. อ่านอย่างเดียว [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | คืนค่าฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ. อ่าน [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | ฟล็ากบูลีนระบุว่าตัวส่วนที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็นจริง ตัวส่วนที่ถูกตัดจะถูกลบ หากเป็นเท็จจะถูกบันทึกในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | กำหนดว่าเท็กซ์ 3D ถูกปิดใช้งานใน SVG หรือไม่. อ่าน **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | รับค่าที่บ่งบอกว่าข้อความถูกแสดงโดยไม่ใช้ลิกเชอร์ เมื่อกำหนดเป็น **true** ลิกเชอร์จะถูกปิดในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | ตั้งค่าที่บ่งบอกว่าข้อความถูกแสดงโดยไม่ใช้ลิกเชอร์ เมื่อกำหนดเป็น **true** ลิกเชอร์จะถูกปิดในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซตสำหรับมาร์คเกอร์. [Aspose.Slides](../../aspose.slides/) เอนจิ้นการเขียน SVG มีวิธีแก้ปัญหานี้: มันตัดส่วนท้ายของเส้นที่มีลูกศรเพื่อให้เส้นไม่ทับกับมาร์คเกอร์ ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว. อ่าน **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. อ่าน [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | คืนค่าสไตล์การแสดงผลของ gradient. อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก. อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | กำหนดคุณภาพการเข้ารหัส JPEG. อ่าน **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | คืนค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไลซ์เมตาฟายล์. อ่าน **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | แสดงระดับการบีบอัดรูปภาพ |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | แสดงอ็อบเจกต์ callback สำหรับบันทึกการอัพเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | คืนค่าและตั้งค่าอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง. อ่าน [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | คืนค่าการตั้งส่าสำหรับการสร้างไฟล์ SVG ที่ง่ายที่สุดและขนาดเล็กที่สุด. อ่านอย่างเดียว [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้าม hyperlink ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. อ่าน **bool**. ค่าเริ่มต้นคือ **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุขณะเรนเดอร์หรือไม่. อ่าน **bool**. ค่าเริ่มต้นคือ true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | กำหนดว่ากรอบข้อความจะรวมอยู่ในพื้นที่เรนเดอร์หรือไม่. อ่าน **bool**. ค่าเริ่มต้นคือ false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | คืนค่าและตั้งค่าอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | คืนค่าการตั้งค่าสำหรับการสร้างไฟล์ SVG ที่แม่นยำที่สุด. อ่านอย่างเดียว [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของโอเปอร์เตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ. เขียน [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | ฟล็ากบูลีนระบุว่าตัวส่วนที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็นจริงส่วนที่ถูกตัดจะถูกลบ หากเป็นเท็จจะถูกบันทึกในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | กำหนดว่าเท็กซ์ 3D ถูกปิดใช้งานใน SVG หรือไม่. เขียน **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | ตั้งค่าที่บ่งบอกว่าข้อความถูกแสดงโดยไม่ใช้ลิกเชอร์ เมื่อกำหนดเป็น **true** ลิกเชอร์จะถูกปิดในผลลัพธ์ที่แสดง โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | ปิดการแยก Gradient FromCornerX และ FromCenter. เขียน **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 ไม่มีความสามารถในการกำหนดอินเซตสำหรับมาร์คเกอร์. [Aspose.Slides](../../aspose.slides/) เอนจิ้นการเขียน SVG มีวิธีแก้ปัญหานี้: มันตัดส่วนท้ายของเส้นที่มีลูกศรเพื่อให้เส้นไม่ทับกับมาร์คเกอร์ ตัวเลือกนี้ปิดพฤติกรรมดังกล่าว. เขียน **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | กำหนดวิธีการจัดการฟอนต์ที่โหลดจากภายนอก. เขียน [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์การแสดงผลของ gradient. เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | กำหนดคุณภาพการเข้ารหัส JPEG. เขียน **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | ตั้งค่าขีดจำกัดความละเอียดต่ำสุดสำหรับการเรสเตอร์ไลซ์เมตาฟายล์. เขียน **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | แสดงระดับการบีบอัดรูปภาพ |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | แสดงอ็อบเจกต์ callback สำหรับบันทึกการอัพเดตความคืบหน้าเป็นเปอร์เซ็นต์. ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | คืนค่าและตั้งค่าอินเทอร์เฟซ callback ที่ให้ผู้ใช้ควบคุมการแปลงรูปร่าง. เขียน [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้าม hyperlink ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ. เขียน **bool**. ค่าเริ่มต้นคือ **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | กำหนดว่าจะทำการหมุนรูปร่างตามที่ระบุขณะเรนเดอร์หรือไม่. เขียน **bool**. ค่าเริ่มต้นคือ true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | กำหนดว่ากรอบข้อความจะรวมอยู่ในพื้นที่เรนเดอร์หรือไม่. เขียน **bool**. ค่าเริ่มต้นคือ false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | กำหนดว่าข้อความบนสไลด์จะถูกบันทึกเป็นกราฟิกหรือไม่. เขียน **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | คืนค่าและตั้งค่าอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนการเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์ไปเป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
|  [SVGOptions](./svgoptions/)() | สร้างอินสแตนซ์ใหม่ของคลาส [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [SVGOptions](./) โดยระบุอ็อบเจกต์ตัวควบคุมการฝังลิงก์. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* คลาส [ISVGOptions](../isvgoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)