---
title: IChartTextBlockFormat
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ.
type: docs
weight: 885
url: /th/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat คลาส

แสดงคุณสมบัติการจัดรูปแบบสำหรับองค์ประกอบข้อความของแผนภูมิ.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | คืนข้อความยึดแนวตั้งใน [TextFrame](../../aspose.slides/textframe/). อ่าน [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | คืนโหมดการปรับขนาดอัตโนมัติของข้อความ. การเปลี่ยนแปลงคุณสมบัตินี้อาจมีผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | หาก [NullableBool::True](../../aspose.slides/nullablebool/) แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | คืนค่ากลีบด้านล่าง (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | คืนค่ากลีบด้านซ้าย (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | คืนค่ากลีบด้านขวา (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | คืนค่ากลีบด้านบน (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการแสดงผล). อ่าน **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่เชื่อมโยง. หากระบุแล้ว การหมุนนี้จะถูกนำไปใช้แยกจากรูปร่าง. กล่าวคือ รูปร่างอาจมีการหมุนเพิ่มเติมจากการหมุนของข้อความเอง. ค่าการหมุนข้อความที่แสดงผลสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | กำหนดทิศทางของข้อความ. ค่าการหมุนข้อความที่แสดงผลสรุปจากคุณสมบัตินี้และมุมกำหนดเองในคุณสมบัติ RotationAngle. อ่าน [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** หากข้อความถูกตัดบรรทัดที่ขอบของ [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2007/2013). อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของอ็อบเจ็กต์ C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | ตั้งข้อความยึดแนวตั้งใน [TextFrame](../../aspose.slides/textframe/). เขียน [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | ตั้งค่าโหมดการปรับขนาดอัตโนมัติของข้อความ. การเปลี่ยนแปลงคุณสมบัตินี้อาจมีผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการเรนเดอร์). เขียน [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | หาก [NullableBool::True](../../aspose.slides/nullablebool/) แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | ตั้งค่ากลีบด้านล่าง (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการเรนเดอร์). เขียน **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | ตั้งค่ากลีบด้านซ้าย (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการเรนเดอร์). เขียน **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | ตั้งค่ากลีบด้านขวา (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการเรนเดอร์). เขียน **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | ตั้งค่ากลีบด้านบน (จุด) ใน [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2013; ใน PowerPoint 2007 ไม่มีผลต่อการเรนเดอร์). เขียน **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | ระบุการหมุนแบบกำหนดเองที่นำไปใช้กับข้อความภายในกล่องขอบเขต. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่เชื่อมโยง. หากระบุแล้ว การหมุนนี้จะถูกนำไปใช้แยกจากรูปร่าง. กล่าวคือ รูปร่างอาจมีการหมุนเพิ่มเติมจากการหมุนของข้อความเอง. ค่าการหมุนข้อความที่แสดงผลสรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดล่วงหน้าในคุณสมบัติ TextVerticalType. เขียน **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | กำหนดทิศทางของข้อความ. ค่าการหมุนข้อความที่แสดงผลสรุปจากคุณสมบัตินี้และมุมกำหนดเองในคุณสมบัติ RotationAngle. เขียน [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** หากข้อความถูกตัดบรรทัดที่ขอบของ [TextFrame](../../aspose.slides/textframe/). การเปลี่ยนแปลงคุณสมบัตินี้อาจส่งผลต่อส่วนของแผนภูมิต่อไปนี้เท่านั้น: [DataLabel](../datalabel/) และ [DataLabelFormat](../datalabelformat/) (รองรับเต็มใน PowerPoint 2007/2013). เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)