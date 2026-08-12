---
title: IXamlOptions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวเลือกที่ควบคุมวิธีการบันทึกเอกสาร XAML.
type: docs
weight: 1
url: /th/aspose.slides.export.xaml/ixamloptions/
---
## IXamlOptions คลาส


Options that control how a XAML document is saved.

```cpp
class IXamlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/isaveoptions/get_defaultregularfont/)() | ส่งคืนฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() | กำหนดว่าการสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/isaveoptions/get_gradientstyle/)() | ส่งคืนรูปแบบการแสดงผลของไล่ระดับสี อ่าน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() | แสดงถึงการทำงานของอินเทอร์เฟซ IOutputSaver. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/isaveoptions/get_progresscallback/)() | แสดงถึงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/get_skipjavascriptlinks/)() | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ อ่าน **bool**. ค่าเริ่มต้นคือ **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/isaveoptions/get_warningcallback/)() | ส่งคืนอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่าจะดำเนินการโหลดต่อหรือยกเลิก อ่าน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ตรรกะของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ตรงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType หรือไม่. ตรงกับตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานเหมือนคำสั่ง C# lock() การล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | การอ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายรายการ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงด้วยค่าที่ระบุ. |
| virtual void [set_DefaultRegularFont](../../aspose.slides.export/isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ตั้งค่าฟอนต์ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นทาง เขียน [System::String](../../system/string/). |
| virtual void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) | กำหนดว่าการสไลด์ที่ซ่อนจะถูกส่งออกหรือไม่. |
| virtual void [set_GradientStyle](../../aspose.slides.export/isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ตั้งค่ารูปแบบการแสดงผลของไล่ระดับสี เขียน [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) | แสดงถึงการทำงานของอินเทอร์เฟซ IOutputSaver. |
| virtual void [set_ProgressCallback](../../aspose.slides.export/isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | แสดงถึงอ็อบเจ็กต์ callback สำหรับบันทึกการอัปเดตความคืบหน้าเป็นเปอร์เซ็นต์ ดู [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/set_skipjavascriptlinks/)(**bool**) | ระบุว่าจะข้ามไฮเปอร์ลิงก์ที่มีการเรียก JavaScript หรือไม่เมื่อบันทึกการนำเสนอ เขียน **bool**. ค่าเริ่มต้นคือ **false**. |
| virtual void [set_WarningCallback](../../aspose.slides.export/isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | ตั้งค่าอ็อบเจ็กต์ที่รับคำเตือนและกำหนดว่าจะดำเนินการโหลดต่อหรือยกเลิก. เขียน [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument template ที่ n เป็น weak pointer (แทน shared). เปิดให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ตรงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานเหมือนคำสั่ง C# lock() การปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## ดูเพิ่มเติม

* คลาส [ISaveOptions](../../aspose.slides.export/isaveoptions/)
* เนมสเปซ [Aspose::Slides::Export::Xaml](../)
* ไลบรารี [Aspose.Slides](../../)