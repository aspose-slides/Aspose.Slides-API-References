---
title: PdfOptions
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ Pdf.
type: docs
weight: 573
url: /th/aspose.slides.export/pdfoptions/
---
## PdfOptions คลาส


Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | มีชุดของแฟลกที่ระบุว่าควรให้สิทธิ์การเข้าถึงอะไรบ้างเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | คืนค่าอาร์เรย์ของชื่อแบบอักษรที่ผู้ใช้กำหนดซึ่ง [Aspose.Slides](../../aspose.slides/) ควรถือเป็นแบบอักษรทั่วไป อ่าน [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | ใช้สีโปร่งใสที่ระบุกับภาพหาก **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ หากกำหนดเป็น **bool**.true จะเลือกอัลกอริธึมการบีบอัดที่เหมาะสมที่สุดสำหรับภาพแต่ละภาพในงานนำเสนอ ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่สร้างมีขนาดเล็กลง |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น อ่าน [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ อ่าน **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | กำหนดว่าควรฝังอักขระทั้งหมดของแบบอักษรหรือเพียงส่วนย่อยที่ใช้ อ่าน **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | กำหนดว่า [Aspose.Slides](../../aspose.slides/) จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่ [Fonts](../../aspose.slides/fonts/) สำหรับโค้ดอักขระที่มากกว่า 127 จะฝังเสมอ รายการแบบอักษรทั่วไปรวมถึงแบบอักษรพื้นฐาน 14 ของ PDF และแบบอักษรที่ผู้ใช้ระบุเพิ่มเติม อ่าน **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | คืนค่าสไตล์ภาพกราเดียนต์ อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | รับค่าสีโปร่งใสของภาพ. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่สร้างขึ้น อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | คืนค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF อ่าน **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | ระบุว่าข้อความควรแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา วิธีนี้สามารถปรับปรุงคุณภาพของข้อความใน PDF ที่สร้างสำหรับแบบอักษรบางแบบ อ่าน **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG อ่าน **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียกใช้ JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | รับโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | คืนค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาเชิงข้อความทั้งหมดในเอกสาร อ่าน [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | คืนค่าและกำหนดอ็อบเจ็กต์ที่รับการแจ้งเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกประเสริฐของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อเนกประเสริฐของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อเนกประเสริฐของออเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกประเสริฐของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
|  [PdfOptions](./pdfoptions/)() | คอนสตรัคเตอร์เริ่มต้น. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของวัตถุแบบค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | มีชุดของแฟลกที่ระบุว่าควรให้สิทธิ์การเข้าถึงอะไรบ้างเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | ตั้งค่าอาร์เรย์ของชื่อแบบอักษรที่ผู้ใช้กำหนดซึ่ง [Aspose.Slides](../../aspose.slides/) ควรถือเป็นแบบอักษรทั่วไป เขียน [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | ใช้สีโปร่งใสที่ระบุกับภาพหาก **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | ระบุว่าควรเลือกการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ หากตั้งเป็น **bool**.true จะเลือกอัลกอริธึมการบีบอัดที่เหมาะสมที่สุดสำหรับภาพแต่ละภาพในงานนำเสนอ ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่สร้างมีขนาดเล็กลง |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้าง เขียน [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True เพื่อวาดกรอบสีดำรอบแต่ละสไลด์ เขียน **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | กำหนดว่าควรฝังอักขระทั้งหมดของแบบอักษรหรือเฉพาะส่วนที่ใช้ เขียน **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | กำหนดว่า [Aspose.Slides](../../aspose.slides/) จะฝังแบบอักษรทั่วไปสำหรับข้อความ ASCII (ช่วงโค้ด 33..127) หรือไม่ [Fonts](../../aspose.slides/fonts/) สำหรับโค้ดอักขระที่มากกว่า 127 จะฝังเสมอ รายการแบบอักษรทั่วไปรวมถึงแบบอักษรพื้นฐาน 14 ของ PDF และแบบอักษรที่ผู้ใช้ระบุเพิ่มเติม เขียน **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์ภาพกราเดียนต์ เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | ตั้งค่าสีโปร่งใสของภาพ. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่สร้าง เขียน **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | ตั้งค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF เขียน **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF เขียน [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | ระบุว่าข้อความควรแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา วิธีนี้สามารถปรับปรุงคุณภาพของข้อความใน PDF ที่สร้างสำหรับแบบอักษรบางแบบ เขียน **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True เพื่อแปลงเมต้าไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG เขียน **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | ตั้งค่าโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | ตั้งค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาเชิงข้อความทั้งหมดในเอกสาร เขียน [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | คืนค่าและกำหนดอ็อบเจ็กต์ที่รับการแจ้งเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกประเสริฐของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ





ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมตัวเลือกที่กำหนดเอง.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// สร้างอินสแตนซ์ของคลาส PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// ตั้งค่าคุณภาพของ Jpeg
pdfOptions->set_JpegQuality(90);
// ตั้งค่าพฤติกรรมสำหรับเมต้าไฟล์
pdfOptions->set_SaveMetafilesAsPng(true);
// ตั้งค่าระดับการบีบอัดข้อความ
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// กำหนดมาตรฐาน PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// บันทึกการนำเสนอเป็น PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมสไลด์ที่ซ่อนอยู่.
```cpp
// สร้างอินสแตนซ์ของคลาส Presentation ที่แสดงไฟล์ PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// สร้างอินสแตนซ์ของคลาส PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// เพิ่มสไลด์ที่ซ่อนอยู่
pdfOptions->set_ShowHiddenSlides(true);
// บันทึกการนำเสนอเป็น PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
ตัวอย่างต่อนี้แสดงวิธีแปลง PowerPoint เป็น PDF ที่มีการป้องกันด้วยรหัสผ่าน.
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงไฟล์ PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// ตั้งค่ารหัสผ่าน PDF และสิทธิ์การเข้าถึง
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// บันทึกการนำเสนอเป็น PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
ตัวอย่างต่อไปนี้แสดงวิธีแปลง PowerPoint เป็น PDF พร้อมบันทึกย่อ.
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่แสดงไฟล์งานนำเสนอ
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* คลาส [IPdfOptions](../ipdfoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)