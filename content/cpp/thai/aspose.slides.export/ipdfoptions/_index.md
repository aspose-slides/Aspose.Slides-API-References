---
title: IPdfOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Pdf.
type: docs
weight: 274
url: /th/aspose.slides.export/ipdfoptions/
---
## IPdfOptions คลาส

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Pdf

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | ประกอบด้วยชุดของแฟล็กที่ระบุว่าจะให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | คืนค่าชุดของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง [Aspose.Slides](../../aspose.slides/) ควรพิจารณาเป็นแบบทั่วไป อ่าน [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | ใช้สีโปร่งแสงที่ระบุกับภาพหาก **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | บ่งบอกว่าควรเลือกการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ หากตั้งค่าเป็น **bool**.true สำหรับภาพทุกภาพในงานนำเสนอจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุด ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้มีขนาดเล็กลง |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น อ่าน [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | คืนค่าแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | ตั้งเป็น true เพื่อวางกรอบสีดำรอบแต่ละสไลด์ อ่าน **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะต้องฝังหรือใช้เพียงส่วนย่อยเท่านั้น อ่าน **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | ตั้งเป็น true เพื่อฝังฟอนต์ true type สำหรับอักขระ ASCII 32-127 [Fonts](../../aspose.slides/fonts/) สำหรับรหัสอักขระที่มากกว่า 127 จะถูกฝังเสมอ อ่าน **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | คืนค่าสไตล์ภาพกราดของสีไล่ระดับ อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | รับสีโปร่งแสงของภาพ. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | ตั้งเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากการนำเสนอเป็นไฟล์ฝังใน PDF ผลลัพธ์ อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ [Ink](../../aspose.slides.ink/) ในเอกสารที่ส่งออก อ่านอย่างเดียว [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | คืนค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF อ่าน **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | แสดงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | บ่งบอกว่าข้อความควรแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ผลลัพธ์สำหรับฟอนต์บางประเภท อ่าน **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | ตั้งเป็น true เพื่อแปลงเมตาฟไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG อ่าน **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | ระบุว่าดอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript ขณะบันทึกการนำเสนอหรือไม่ อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | รับโหมดที่สไลด์จัดวางบนหน้าขณะส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | คืนค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร อ่าน [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | คืนอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่าจะดำเนินการโหลดต่อหรือหยุดอ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ที่ช่วยให้สามารถทำแฮชของอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่าตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ที่ช่วยให้ทำการคล cloning ของประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | ประกอบด้วยชุดของแฟล็กที่ระบุว่าจะให้สิทธิ์การเข้าถึงใดเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | ตั้งชุดของชื่อฟอนต์ที่ผู้ใช้กำหนดซึ่ง [Aspose.Slides](../../aspose.slides/) ควรพิจารณาเป็นแบบทั่วไป เขียน [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | ใช้สีโปร่งแสงที่ระบุกับภาพหาก **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | บ่งบอกว่าควรเลือกการบีบอัดที่มีประสิทธิภาพที่สุด (แทนค่าปริยาย) สำหรับแต่ละภาพโดยอัตโนมัติหรือไม่ หากตั้งค่าเป็น **bool**.true สำหรับภาพทุกภาพในงานนำเสนอจะเลือกอัลกอริทึมการบีบอัดที่เหมาะสมที่สุด ซึ่งจะทำให้ขนาดของเอกสาร PDF ที่ได้มีขนาดเล็กลง |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | ระดับการปฏิบัติตามที่ต้องการสำหรับเอกสาร PDF ที่สร้างขึ้น เขียน [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งแบบอักษรที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | ตั้งเป็น true เพื่อวางกรอบสีดำรอบแต่ละสไลด์ เขียน **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | กำหนดว่าตัวอักษรทั้งหมดของฟอนต์จะต้องฝังหรือใช้เพียงส่วนย่อยเท่านั้น เขียน **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | ตั้งเป็น true เพื่อฝังฟอนต์ true type สำหรับอักขระ ASCII 32-127 [Fonts](../../aspose.slides/fonts/) สำหรับรหัสอักขระที่มากกว่า 127 จะฝังเสมอ เขียน **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งสไตล์ภาพกราดของสีไล่ระดับ เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | ตั้งสีโปร่งแสงของภาพ. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | ตั้งเป็น true เพื่อแปลงข้อมูล OLE ทั้งหมดจากการนำเสนอเป็นไฟล์ฝังใน PDF ผลลัพธ์ เขียน **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | ตั้งค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF เขียน **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | ตั้งรหัสผ่านผู้ใช้เพื่อปกป้องเอกสาร PDF เขียน [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | แสดงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | บ่งบอกว่าข้อความควรแปลงเป็นบิตแมพและบันทึกเป็น PDF เมื่อแบบอักษรไม่รองรับการทำตัวหนา วิธีนี้สามารถเพิ่มคุณภาพของข้อความใน PDF ผลลัพธ์สำหรับฟอนต์บางประเภท เขียน **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | ตั้งเป็น true เพื่อแปลงเมตาฟไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG เขียน **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | ระบุว่าดอกสารที่สร้างควรรวมสไลด์ที่ซ่อนไว้หรือไม่ ค่าเริ่มต้นคือ **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript ขณะบันทึกการนำเสนอหรือไม่ เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | ตั้งโหมดที่สไลด์จัดวางบนหน้าขณะส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | ตั้งค่าที่กำหนดความละเอียดของภาพภายในเอกสาร PDF. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | ระบุประเภทการบีบอัดที่จะใช้กับเนื้อหาข้อความทั้งหมดในเอกสาร เขียน [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่าจะดำเนินการโหลดต่อหรือหยุด เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตตัวที่ n ให้เป็น weak pointer (แทน shared) ช่วยให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/) ที่ช่วยให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สร้างโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ISaveOptions](../isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)