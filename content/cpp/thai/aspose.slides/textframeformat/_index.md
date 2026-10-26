---
title: TextFrameFormat
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: มีคุณสมบัติ formatTextFrameFormatting ของ TextFrame
type: docs
weight: 5461
url: /th/aspose.slides/textframeformat/
---
## TextFrameFormat คลาส

Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## เมธอด

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | คืนค่าข้อความยึดแนวตั้งใน [TextFrame](../textframe/). อ่าน [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | คืนค่าโหมดการปรับขนาดอัตโนมัติของข้อความ. อ่าน [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | หาก [NullableBool::True](../nullablebool/) แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. อ่าน [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | คืนจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นค่าบวก. หากไม่เป็นเช่นนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. อ่าน **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | คืนค่าช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด). ควรใช้เฉพาะเมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นค่าบวก. หากไม่เป็นเช่นนั้นค่าจะถูกตั้งเป็นศูนย์. อ่าน **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | รับการคงข้อความให้อยู่แบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3 มิติถูกใช้. อ่าน **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | คืนค่ากำหนดขอบล่าง (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | คืนค่ากำหนดขอบซ้าย (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | คืนค่ากำหนดขอบขวา (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | คืนค่ากำหนดขอบบน (จุด) ใน [TextFrame](../textframe/). อ่าน **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนผู้ปิดแบบพาเรนท์ [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมา. หากระบุ จะถูกนำไปใช้แยกจากรูปร่าง. ซึ่งหมายความว่ารูปร่างอาจมีการหมุนเพิ่มเติมนอกจากข้อความเองที่มีการหมุน. ค่าการหมุนของข้อความที่ได้สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. อ่าน **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | กำหนดทิศทางของข้อความ. ค่าการหมุนของข้อความที่ได้สรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. อ่าน [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่แสดงคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับข้อความ. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | รับรูปร่างการห่อข้อความ. อ่าน [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** หากข้อความถูกห่อที่ขอบของ [TextFrame](../textframe/). อ่าน [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลการจัดรูปแบบกรอบข้อความที่มีผลโดยการสืบทอด. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่า hash code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับอ็ปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริ่งและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริ่งหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่ใช้ร่วมโดยค่าที่ระบุ. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | ตั้งค่าข้อความยึดแนวตั้งใน [TextFrame](../textframe/). เขียน [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | ตั้งค่าโหมดการปรับขนาดอัตโนมัติของข้อความ. เขียน [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | หาก [NullableBool::True](../nullablebool/) แล้วข้อความควรอยู่กึ่งกลางในกล่องในแนวนอน. เขียน [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | ตั้งค่าจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่านี้ต้องเป็นค่าบวก. หากไม่เป็นเช่นนั้นค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าไม่กำหนด. เขียน **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | ตั้งค่าช่องว่างระหว่างคอลัมน์ข้อความในพื้นที่ข้อความ (เป็นจุด). ควรใช้เฉพาะเมื่อมีมากกว่าหนึ่งคอลัมน์. ค่านี้ต้องเป็นค่าบวก. หากไม่เป็นเช่นนั้นค่าจะถูกตั้งเป็นศูนย์. เขียน **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | ตั้งค่าการคงข้อความให้อยู่แบนแม้ว่าจะมีเอฟเฟกต์การหมุน 3 มิติถูกใช้. เขียน **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | ตั้งค่าขอบล่าง (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | ตั้งค่าขอบซ้าย (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | ตั้งค่าขอบขวา (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | ตั้งค่าขอบบน (จุด) ใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | ระบุการหมุนแบบกำหนดเองที่ใช้กับข้อความภายในกรอบ. หากไม่ได้ระบุ จะใช้การหมุนของรูปร่างที่แนบมา. หากระบุ จะถูกนำไปใช้แยกจากรูปร่าง. ซึ่งหมายความว่ารูปร่างอาจมีการหมุนเพิ่มเติมนอกจากข้อความเองที่มีการหมุน. ค่าการหมุนของข้อความที่ได้สรุปจากคุณสมบัตินี้และประเภทแนวตั้งที่กำหนดไว้ในคุณสมบัติ TextVerticalType. เขียน **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | กำหนดทิศทางของข้อความ. ค่าการหมุนของข้อความที่ได้สรุปจากคุณสมบัตินี้และมุมที่กำหนดในคุณสมบัติ RotationAngle. เขียน [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | ตั้งรูปร่างการห่อข้อความ. เขียน [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** หากข้อความถูกห่อที่ขอบของ [TextFrame](../textframe/). เขียน [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่ใช้ร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่ใช้ร่วม. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่ใช้ร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointer หรือ ThisProtector. |
|  [TextFrameFormat](./textframeformat/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [TextFrameFormat](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริ่ง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นใช้ smart pointer หรือ ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [ITextFrameFormat](../itextframeformat/)
* คลาส [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* เนมสเปซ [Aspose::Slides](../)
* Library [Aspose.Slides](../../)