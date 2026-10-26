---
title: MarkdownSaveOptions
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แสดงตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอเป็น markdown.
type: docs
weight: 547
url: /th/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions คลาส


Represents options that control how presentation should be saved to markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | ระบุตำแหน่งฐานที่ไฟล์เอกสารพร้อมทรัพยากรจะถูกบันทึก ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ส่งคืนแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นฉบับ อ่าน [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ ค่าเริ่มต้นคือ **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ ค่าเริ่มต้นคือ **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ส่งคืนสไตล์การแสดงผลของเกรเดียนท์ อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | ระบุวิธีจัดการกับอักขระช่องว่างธรรมดาที่ซ้ำกันระหว่างการส่งออก Markdown. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ ค่าเริ่มต้นคือ **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | ระบุว่าค่าเอกสารที่สร้างควรมีบรรทัดใหม่เป็น \r(Macintosh) หรือ \n(Unix) หรือ \r\n(Windows) ค่าเริ่มต้นคือ **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | ถ้ากำหนดเป็น **true** จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย ค่าเริ่มต้นคือ **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | ระบุว่าค่าเอกสารที่สร้างควรแสดงความเห็นหรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | ระบุว่าค่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | ระบุว่าค่าเอกสารที่สร้างควรแสดงหมายเลขของแต่ละสไลด์หรือไม่ ค่าเริ่มต้นคือ **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ อ่าน **bool** ค่าเริ่มต้นคือ **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | รับสตริงฟอร์แมตที่ใช้สำหรับหัวเลขสไลด์ในผลลัพธ์ Markdown ฟอร์แมตต้องมีตัวแทน \"{0}\" ที่จะถูกแทนที่ด้วยดัชนีสไลด์ระหว่างการส่งออก ตัวอย่าง: \"# Slide {0}\" จะให้ผลลัพธ์ \"# Slide 1\", \"# Slide 2\" เป็นต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/). |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | เป็นคอนสตรัคเตอร์. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้ทำการโคลนประเภทที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงประเภทค่าอ็อบเจ็กต์กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | ระบุตำแหน่งฐานที่ไฟล์เอกสารพร้อมทรัพยากรจะถูกบันทึก ค่าเริ่มต้นคือไดเรกทอรีปัจจุบันของแอปพลิเคชัน. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ตั้งค่าแบบอักษรที่ใช้ในกรณีไม่พบแบบอักษรต้นฉบับ เขียน [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ ค่าเริ่มต้นคือ **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | ระบุสเปค markdown เพื่อแปลงงานนำเสนอ ค่าเริ่มต้นคือ **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ตั้งค่าสไตล์การแสดงผลของเกรเดียนท์ เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | ระบุวิธีจัดการกับอักขระช่องว่างธรรมดาที่ซ้ำกันระหว่างการส่งออก Markdown. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | ระบุชื่อโฟลเดอร์เพื่อบันทึกรูปภาพ ค่าเริ่มต้นคือ **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | ระบุว่าค่าเอกสารที่สร้างควรมีบรรทัดใหม่เป็น \r(Macintosh) หรือ \n(Unix) หรือ \r\n(Windows) ค่าเริ่มต้นคือ **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | เป็นอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | ถ้ากำหนดเป็น **true** จะลบบรรทัดที่ว่างหรือมีเพียงช่องว่างออกจากผลลัพธ์ Markdown ขั้นสุดท้าย ค่าเริ่มต้นคือ **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | ระบุว่าค่าเอกสารที่สร้างควรแสดงความเห็นหรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | ระบุว่าค่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | ระบุว่าค่าเอกสารที่สร้างควรแสดงหมายเลขของแต่ละสไลด์หรือไม่ ค่าเริ่มต้นคือ **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกงานนำเสนอ เขียน **bool** ค่าเริ่มต้นคือ **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | ตั้งค่าสตริงฟอร์แมตที่ใช้สำหรับหัวเลขสไลด์ในผลลัพธ์ Markdown ฟอร์แมตต้องมีตัวแทน \"{0}\" ที่จะถูกแทนที่ด้วยดัชนีสไลด์ระหว่างการส่งออก ตัวอย่าง: \"# Slide {0}\" จะให้ผลลัพธ์ \"# Slide 1\", \"# Slide 2\" เป็นต้น |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | ส่งคืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำให้เกิดโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามชนิด

| Typedef | Description |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | ถูกเรียกสำหรับแต่ละภาพที่ไม่ใช่ SVG (bitmap หรือ metafile) ระหว่างการส่งออก Markdown คืน **true** เพื่อใช้ *link* ที่ระบุ หรือ **false** เพื่อใช้ตรรกะการบันทึกเริ่มต้น. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | ถูกเรียกสำหรับแต่ละภาพ SVG ระหว่างการส่งออก Markdown คืน **true** เพื่อใช้ *link* ที่ระบุ หรือ **false** เพื่อใช้ตรรกะการบันทึกเริ่มต้น. |

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## ดูเพิ่มเติม

* คลาส [SaveOptions](../saveoptions/)
* เนมสเพซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)