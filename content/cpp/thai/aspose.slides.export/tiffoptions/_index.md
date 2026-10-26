---
title: TiffOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF.
type: docs
weight: 768
url: /th/aspose.slides.export/tiffoptions/
---
## TiffOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ TIFF

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจำนวนเต็มแบบ C# ที่สองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจำนวนเต็มแบบ C# ที่สองค่า NaN ถูกพิจารณาเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | ระบุอัลกอริธึมสำหรับการแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) ถูกตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) อ่าน [BlackWhiteConversionMode](../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | ระบุประเภทการบีบอัด อ่าน [TiffCompressionTypes](../tiffcompressiontypes/) |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | คืนค่าแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_DpiX](./get_dpix/)() override | ระบุความละเอียดแนวนอนเป็น dot ต่อ นิ้ว อ่าน **uint32_t** |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | ระบุความละเอียดแนวตั้งเป็น dot ต่อ นิ้ว อ่าน **uint32_t** |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | คืนค่าสไตล์การแสดงผลของกราดิเอนท์ อ่าน [GradientStyle](../../aspose.slides/gradientstyle/) |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างจะคำนวณตามค่าขนาดสไลด์การนำเสนอ อ่าน [System::Drawing::Size](../../system.drawing/size/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของอ็อบเจ็กต์ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง อ่าน [ImagePixelFormat](../imagepixelformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | ระบุว่าหนังสือเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false** |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript เมื่อบันทึกการนำเสนอหรือไม่ อ่าน **bool** ค่าเริ่มต้นคือ **false** |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | รับโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/) |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | คืนค่าหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอเนกประสงค์ของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอ้อะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสทำการคัดลอก |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอ้อะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสทำการคัดลอก |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | ระบุอัลกอริธึมสำหรับการแปลงภาพสีเป็นภาพขาวดำ ตัวเลือกนี้จะใช้ก็ต่อเมื่อ [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) ถูกตั้งค่าเป็น [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) หรือ [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) เขียน [BlackWhiteConversionMode](../blackwhiteconversionmode/) ค่าเริ่มต้นคือ [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | ระบุประเภทการบีบอัด เขียน [TiffCompressionTypes](../tiffcompressiontypes/) |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/) |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | ระบุความละเอียดแนวนอนเป็น dot ต่อ นิ้ว เขียน **uint32_t** |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | ระบุความละเอียดแนวตั้งเป็น dot ต่อ นิ้ว เขียน **uint32_t** |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์การแสดงผลของกราดิเอนท์ เขียน [GradientStyle](../../aspose.slides/gradientstyle/) |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | ระบุขนาดของภาพ TIFF ที่สร้างขึ้น ค่าเริ่มต้นคือ 0x0 ซึ่งหมายความว่าขนาดของภาพที่สร้างจะคำนวณตามค่าขนาดสไลด์การนำเสนอ เขียน [System::Drawing::Size](../../system.drawing/size/) |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | ระบุรูปแบบพิกเซลสำหรับภาพที่สร้าง เขียน [ImagePixelFormat](../imagepixelformat/) |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/) |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | ระบุว่าหนังสือเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false** |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript เมื่อบันทึกการนำเสนอหรือไม่ เขียน **bool** ค่าเริ่มต้นคือ **false** |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | ตั้งค่าโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/) |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | คืนค่าหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือถูกยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) รองรับการสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
|  [TiffOptions](./tiffoptions/)() | คอนสตรัคเตอร์เริ่มต้น |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดเริ่มต้น
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงไฟล์การนำเสนอ
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// บันทึกการนำเสนอเป็นเอกสาร TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยขนาดที่กำหนดเอง
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์ Presentation
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// สร้างอ็อบเจ็กต์ของคลาส TiffOptions
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// ตั้งค่าประเภทการบีบอัด
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// ประเภทการบีบอัด
// Default - ระบุโหมดการบีบอัดเริ่มต้น (LZW).
// None - ระบุว่าไม่มีการบีบอัด.
// CCITT3
// CCITT4
// LZW
// RLE
// ความลึกขึ้นอยู่กับประเภทการบีบอัดและไม่สามารถตั้งค่าได้ด้วยตนเอง.
// หน่วยความละเอียดจะเท่ากับ "2" เสมอ (dot ต่อ นิ้ว)
// ตั้งค่า DPI ของภาพ
opts->set_DpiX(200);
opts->set_DpiY(100);
// ตั้งค่าขนาดภาพ
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Save the presentation to TIFF with specified image size
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น TIFF ด้วยรูปแบบพิกเซลของภาพที่กำหนดเอง
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์ Presentation
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// บันทึกการนำเสนอเป็น TIFF ด้วยขนาดภาพที่ระบุ
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* คลาส [ITiffOptions](../itiffoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)