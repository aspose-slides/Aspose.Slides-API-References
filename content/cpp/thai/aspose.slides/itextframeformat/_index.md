---
title: ITextFrameFormat
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: มีคุณสมบัติการจัดรูปแบบของ TextFrame
type: docs
weight: 4083
url: /th/aspose.slides/itextframeformat/
---
## ITextFrameFormat คลาส

มีคุณสมบัติการจัดรูปแบบของ [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ของ C# โดยที่ NaN สองค่าถูกนับว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตามสไตล์ของ C# โดยที่ NaN สองค่าถูกนับว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | คืนข้อความ anchor แนวตั้งใน [TextFrame](../textframe/). อ่าน [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | คืนโหมดการปรับขนาดอัตโนมัติของข้อความ. อ่าน [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | หาก [NullableBool::True](../nullablebool/) ข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | คืนค่าจำนวนคอลัมน์ในพื้นที่ข้อความ ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์ ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด อ่าน **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | คืนค่าระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด) นี้ควรใช้เฉพาะเมื่อมีคอลัมน์มากกว่า 1 ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์ อ่าน **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | คืนค่า หรือ ตั้งค่าให้ข้อความไม่แสดงในฉาก 3D ทั้งหมด. อ่าน **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | คืนค่าขอบล่าง (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | คืนค่าขอบซ้าย (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | คืนค่าขอบขวา (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | คืนค่าขอบบน (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องรอบข้อความ หากไม่ได้ระบุ จะใช้การหมุนของรูปที่แนบมา หากระบุแล้วจะนำไปใช้แยกจากรูป ซึ่งรูปอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมัน ค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | คืนสไตล์ของข้อความ. อ่านอย่างเดียว [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | กำหนดทิศทางของข้อความ ค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และมุมกำหนดในคุณสมบัติ RotationAngle. อ่าน [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่แสดงคุณสมบัติเส้น 3 มิติสำหรับข้อความ. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | รับรูปร่างการบรรทัดข้อความ. อ่าน [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** หากข้อความถูกบรรทัดที่ขอบของ [TextFrame](../textframe/). อ่าน [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยใช้การสืบทอด. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | ตั้งข้อความ anchor แนวตั้งใน [TextFrame](../textframe/). เขียน [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | ตั้งโหมดการปรับขนาดอัตโนมัติของข้อความ. เขียน [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | หาก [NullableBool::True](../nullablebool/) แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. เขียน [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | ตั้งจำนวนคอลัมน์ในพื้นที่ข้อความ ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์ ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. เขียน **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | ตั้งระยะห่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด) นี้ใช้เฉพาะเมื่อมีคอลัมน์มากกว่า 1 ค่านี้ต้องเป็นจำนวนบวก มิฉะนั้นค่าจะถูกตั้งเป็นศูนย์. เขียน **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | คืนค่า หรือ ตั้งค่าให้ข้อความไม่แสดงในฉาก 3D ทั้งหมด. เขียน **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | ตั้งค่าขอบล่าง (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | ตั้งค่าขอบซ้าย (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | ตั้งค่าขอบขวา (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | ตั้งค่าขอบบน (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกล่องรอบข้อความ หากไม่ได้ระบุ จะใช้การหมุนของรูปที่แนบมา หากระบุแล้วจะนำไปใช้แยกจากรูป ซึ่งรูปอาจมีการหมุนเพิ่มเติมในขณะที่ข้อความเองก็มีการหมุนของมัน ค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ล่วงหน้าในคุณสมบัติ TextVerticalType. เขียน **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | กำหนดทิศทางของข้อความ ค่าการหมุนของข้อความที่สรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. เขียน [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | ตั้งรูปร่างการบรรทัดข้อความ. เขียน [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** หากข้อความถูกบรรทัดที่ขอบของ [TextFrame](../textframe/). เขียน [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)