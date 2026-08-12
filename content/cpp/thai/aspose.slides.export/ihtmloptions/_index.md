---
title: IHtmlOptions
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงตัวเลือกการส่งออก HTML.
type: docs
weight: 222
url: /th/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions คลาส


Represents a HTML exporting options.

```cpp
class IHtmlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style โดยที่ NaN สองค่าถูกพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C#-style โดยที่ NaN สองค่าถูกพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | ส่งคืนฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ อ่าน [System::String](../../system/string/) |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | แฟล็กบูลีนบ่งบอกว่าชิ้นส่วนที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็นจริงส่วนที่ถูกตัดจะถูกลบ หากเป็นเท็จจะถูกจัดเรียงเป็นซีเรียลในเอกสาร (ซึ่งอาจทำให้ไฟล์ใหญ่ขึ้น) อ่าน **bool** |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | รับค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false** |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ส่งคืนสไตล์ภาพของการไล่สี อ่าน [GradientStyle](../../aspose.slides/gradientstyle/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() | ส่งคืนเทมเพลต HTML อ่าน [IHtmlFormatter](../ihtmlformatter/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของอ็อบเจ็กต์ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | ส่งคืนค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF อ่าน **uint8_t** |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | แสดงระดับการบีบอัดรูปภาพ อ่าน [PicturesCompression](../picturescompression/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | แสดงอ็อบเจ็กต์คอลแบ็คสำหรับบันทึกการอัปเดตความคืบหน้าแบบเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ **false** |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | ระบุว่าควรข้ามไฮเพอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกการนำเสนอหรือไม่ อ่าน **bool** ค่าเริ่มต้นคือ **false** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() | ส่งคืนตัวเลือกรูปแบบภาพสไลด์ อ่าน [ISlideImageFormat](../islideimageformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | รับโหมดที่สไลด์จะถูกวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/) |
| virtual **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() | ตั้งเป็น true เพื่อไม่รวมแอตทริบิวต์ width และ height จากคอนเทนเนอร์ SVG - จะทำให้การวางเลย์เอาต์ตอบสนองต่อขนาด ปรับเป็น false ในกรณีอื่น อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | ส่งคืนอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เหมือนตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลยจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้คอนสตรัคเตอร์คัดลอกซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลยจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้คอนสตรัคเตอร์คัดลอกซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งค่าฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ เขียน [System::String](../../system/string/) |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | แฟล็กบูลีนบ่งบอกว่าชิ้นส่วนที่ถูกตัดจะคงอยู่เป็นส่วนหนึ่งของเอกสารหรือไม่ หากเป็นจริงจะลบชิ้นส่วนที่ถูกตัด หากเป็นเท็จจะทำการซีเรียลไลซ์ในเอกสาร (อาจทำให้ไฟล์ใหญ่ขึ้น) เขียน **bool** |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | ตั้งค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์หรือไม่ เมื่อกำหนดเป็น **true** ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์ โดยค่าเริ่มต้นคุณสมบัตินี้ตั้งเป็น **false** |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งสไตล์ภาพของการไล่สี เขียน [GradientStyle](../../aspose.slides/gradientstyle/) |
| virtual void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) | ตั้งค่าเทมเพลต HTML เขียน [IHtmlFormatter](../ihtmlformatter/) |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | ตั้งค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF เขียน **uint8_t** |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | แสดงระดับการบีบอัดรูปภาพ เขียน [PicturesCompression](../picturescompression/) |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | แสดงอ็อบเจ็กต์คอลแบ็คสำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ **false** |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | ระบุว่าควรข้ามไฮเพอร์ลิงก์ที่มีการเรียก JavaScript เมื่อบันทึกการนำเสนอหรือไม่ เขียน **bool** ค่าเริ่มต้นคือ **false** |
| virtual void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) | ตั้งตัวเลือกรูปแบบภาพสไลด์ เขียน [ISlideImageFormat](../islideimageformat/) |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | ตั้งโหมดที่สไลด์จะวางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/) |
| virtual void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) | ตั้งเป็น true เพื่อไม่รวมแอตทริบิวต์ width และ height จากคอนเทนเนอร์ SVG - จะทำให้การจัดวางตอบสนองต่อขนาด ตั้งเป็น false ในกรณีอื่น เขียน **bool** |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [ISaveOptions](../isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)